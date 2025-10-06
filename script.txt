document.getElementById('contact-form').addEventListener('submit', function(e) {
    e.preventDefault();
    document.getElementById('contact-response').innerText = "Thanks for your message! (This is a demo, no real email is sent.)";
});
