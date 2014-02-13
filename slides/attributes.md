## Attributes
Here are some examples

- Autofocus
- dropzone
- data-*



    <article
      id="electriccars"
      data-columns="3"
      data-indexnumber="12314"
      data-parent="cars">
    </article>

    var article = document.querySelector('#electriccars'),
                  data = article.dataset;

    article::before {
      content: attr(data-parent);
    }

Read about them here
[Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)

note: 
  Autofocus - The element should be automatically focused after the page loaded.

  Dropzone - Indicates that the element accept the dropping of content on it.
  
  Data - This class of attributes, called custom data attributes, allows proprietary information to be exchanged between the HTML and its DOM representation that may be used by scripts. All such custom data are available via the HTMLElement interface of the element the attribute is set on. The HTMLElement.dataset property gives access to them.