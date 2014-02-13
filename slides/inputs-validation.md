### WHAT ABOUT VALIDATION OMG

Thats why new validation libraies use the 'required' attribute

    <form class="cmxform" id="commentForm" method="get" action="">
      <fieldset>
        <legend>Please provide your name, email address (won't be published) and a comment</legend>
        <label for="cname">Name (required, at least 2 characters)</label>
        <input id="cname" name="name" minlength="2" type="text" required/>
        <label for="cemail">E-Mail (required)</label>
        <input id="cemail" type="email" name="email" required/>
        <label for="curl">URL (optional)</label>
        <input id="curl" type="url" name="url"/>
        <input class="submit" type="submit" value="Submit"/>
      </fieldset>
    </form>

[jQuery Validation](http://jqueryvalidation.org/documentation/)