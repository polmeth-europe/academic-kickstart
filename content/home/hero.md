+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "PolMeth Europe 2021"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "uhh-logo-web.gif"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  #color = "#009cd1"

  # Background gradient.
  gradient_start = "#009cd1"
  gradient_end = "#90d2e8"

  # Background image.
  # image = ""  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "https://gather.town/app/og6t5BTUEdgrSaNt/PolMethEurope"
  label = "Join PolMeth Europe"
  icon_pack = "fas"
  icon = "sign-in-alt"

#[cta_alt]
#  url = "#programme"
#  label = "Conference Programme"

# Note. An optional note to show underneath the links.
[cta_note]
  label = '<a class="js-github-release" href="https://sourcethemes.com/academic/updates" data-repo="gcushen/hugo-academic">Already registered?<!-- V --></a>'
+++
PolMeth is (finally) coming to Europe.

**You can still register for the PolMeth Europe Meeting between March 17th and March 19th 2021, hosted online by the University of Hamburg. There are no fees for the inaugural PolMeth Europe Meeting. Please note that you will need the email address you register with to access the virtual conference space. If you are already registered you can directly join the virtual PolMeth Europe meeting below.**

{{< rawhtml >}}
<form id="fs-frm" name="registration-form" accept-charset="utf-8" action="https://formspree.io/f/xknpladj" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name:</label><br>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
     <br><br><label for="affiliation">Affiliation:</label><br>
    <input type="text" name="aff" id="affiliation" placeholder="Your Affiliation" required="">
    <br><br><label for="email-address">Email Address:</label><br>
    <input type="email" name="_replyto" id="email-address" placeholder="email@mail.edu" required="">
    <br><br><label for="role">Your Role:</label><br>
    <select name="role" id="role" required="">
        <option value="Select" selected="" disabled="">Select your Role</option>
      	<option value="participant">Participant</option>
      	<option value="presenter">Presenter</option>
      </select>
    <input type="hidden" name="_subject" id="email-subject" value="Registration Form Submission">
  </fieldset>
  <input type="submit" value="Register">
</form><br><br>
{{< /rawhtml >}}
