<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,
      initial-scale=1.0">
    <title>Contact Us - Jersey.Com</title>
      <h2>Contact Us</h2>
      <p>If you have any questions, please feel free to drop us a message below. We’d love to hear from you!</p> <form action="/submit_contact" method="POST">
        <div class="form-group">
          <label for="name">Name</label>
          <input type="text" id="name" name="name" required>
        </div> <div class="form-group">
          <label for="email">Email</label>
          <input type="email" id="email" name="email" required>
</div>
        <div class="form-group">
  <label for="message">Message</label>
          <textarea id="message" name="message" rows="5" required>
          </textarea>
        </div>
        <div class="form-group">
          <input type="submit" value="Send Message">
        </div>
      </form>
    </div>
  </body>
</html>
