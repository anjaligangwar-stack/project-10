 FAQ Section - Left Questions | Right Image Layout

A clean, responsive FAQ layout with accordion functionality.

 Problem Faced
FAQ questions were taking 100% width. The image was pushed below the questions instead of showing on the right side.

✅ Solution
1.  Created a main wrapper `faq-main` with `display: flex`
2.  Wrapped all FAQ boxes inside `faq-left` div (50% width)
3.  Kept image in separate `faq-img` div (50% width)
4.  Used `classList.toggle('show')` for accordion open/close
💻 Code Snippet
 HTML Structure
html
<section class="faq-main">
  <div class="faq-left">
    <div class="faq-box">...</div>
    <div class="faq-box">...</div>
  </div>
  <div class="faq-img">
    <img src="teampic.png" alt="FAQ">
  </div>
</section>
links:https://anjaligangwar-stack.github.io/project-10/