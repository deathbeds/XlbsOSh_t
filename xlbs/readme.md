    try:
      from . import __init__
    except:
      import __init__

{{__init__.__doc__}}
  
    with __import__('pidgy').pidgyLoader():
      try:
        from . import skateparks, demonstration, hyperactive, demolition, dead_pixels
      except:
        import skateparks, demonstration, hyperactive, demolition, dead_pixels
