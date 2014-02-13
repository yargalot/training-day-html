## How do I use it in js?

Simply put

    if (Modernizr.localstorage) {
      localstoage.set('herp', 'derp')
    } else  {
      $.cookie('jquery sucks')
    }
