---
layout: page
title: Contact
permalink: /contact/
---

If you prefer to receive messages through a contact form, there is a placeholder form below. To make the form send messages to your email, replace `{your_form_id}` with your Formspree form ID or configure another backend.

<form action="https://formspree.io/f/{your_form_id}" method="POST">
  <p>
    <label>Name<br>
      <input type="text" name="name" required>
    </label>
  </p>
  <p>
    <label>Email<br>
      <input type="email" name="_replyto" required>
    </label>
  </p>
  <p>
    <label>Message<br>
      <textarea name="message" rows="6" required></textarea>
    </label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

Fallback (mailto):

- If you prefer not to use an external service, use this mailto link to send email: [Send email](mailto:ricardo.freguglia@ufjf.br)

How to activate the form (options):

1. Formspree (recommended for static sites):
   - Go to https://formspree.io and create a form; copy the form ID and replace `{your_form_id}` in the form action above.
2. Netlify Forms: if you host on Netlify I can adapt the form to work without an external backend.
3. Use the mailto link if you do not want to configure any service.

Tell me which option you prefer and I will configure it for you (for example: "use Formspree and my form ID is abcde123"), or upload the PDF of your CV and I will add it and update the download link.
