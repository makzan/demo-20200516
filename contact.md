---
layout: layout.html
---

# Contact us

<form name="contact" method="POST" data-netlify="true" enctype="multipart/form-data">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <label>Attachment:
      <input type="file" name="attachment">
    </label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>