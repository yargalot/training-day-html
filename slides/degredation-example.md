## How do I use it?

Simply put

    if (Modernizr.localstorage) {
      localstoage.set('herp', 'derp')
    } else  {
      $.cookie('jquery sucks')
    }
