---
layout: default
title: Contact Us Form
description: Please use this form to contact us
---
<center>
    <!-- modify this form HTML and place wherever you want your form -->
    <form
      action="https://formspree.io/f/xdkenqyv"
      method="POST"
    >
        <label>Name:</label><br>
        <input type="text" name="name" size="40"><br>
        <br>
        <label>Email Address:</label><br>
        <input type="email" name="email" size="40"><br>
        <br>
        <label>Message:</label><br>
        <textarea name="message" rows="10" cols="40"></textarea><br>
        <br>
        <!-- your other form fields go here -->
        <button type="submit">Send</button>
    </form>
</center>