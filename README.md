<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="An enhanced HTML5 form with lists, tables, and media for better accessibility and usability.">
    <title>Enhanced HTML5 Form</title>
</head>
<body>

    <header>
        <h1>Enhanced HTML5 Form</h1>
        <p>This form demonstrates lists, tables, media, and HTML5 form validation.</p>
    </header>

    <main>
        <!-- Example List -->
        <section>
            <h2>Instructions</h2>
            <ol>
                <li>Fill in all required fields.</li>
                <li>Ensure the email address is valid.</li>
                <li>Review the table before submitting.</li>
            </ol>
        </section>

        <!-- Example Table -->
        <section>
            <h2>Available Services</h2>
            <table border="1" cellpadding="5" cellspacing="0">
                <caption>Service Packages</caption>
                <thead>
                    <tr>
                        <th>Service</th>
                        <th>Description</th>
                        <th>Price (KES)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Web Design</td>
                        <td>Responsive website creation</td>
                        <td>50,000</td>
                    </tr>
                    <tr>
                        <td>SEO Optimization</td>
                        <td>Improve search rankings</td>
                        <td>30,000</td>
                    </tr>
                    <tr>
                        <td>Maintenance</td>
                        <td>Monthly updates and backups</td>
                        <td>10,000</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Example Media -->
        <section>
            <h2>Watch Our Introduction Video</h2>
            <video part="video" autoplay crossorigin="" width="500" controls playsinline="" muted="" src="https://videos.pexels.com/video-files/4614907/4614907-uhd_2560_1440_30fps.mp4" preload="metadata"><track kind="metadata" label="cuepoints" data-removeondestroy=""></video>
            <!-- <video controls width="320">
                <source src="intro.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video> -->
        </section>

        <!-- Form -->
        <section>
            <h2>Contact Form</h2>
            <form action="#" method="post" autocomplete="on">
                <fieldset>
                    <legend>Personal Information</legend>

                    <label for="fullname">Full Name:</label><br>
                    <input type="text" id="fullname" name="fullname" placeholder="Juma sam" required><br><br>

                    <label for="email">Email:</label><br>
                    <input type="email" id="email" name="email" placeholder="example@mail.com" required><br><br>

                    <label for="dob">Date of Birth:</label><br>
                    <input type="date" id="dob" name="dob" required><br><br>

                    <label for="phone">Phone Number:</label><br>
                    <input type="tel" id="phone" name="phone" placeholder="+254700000090" pattern="\+?\d{10,15}" required><br><br>
                </fieldset>

                <fieldset>
                    <legend>Service Selection</legend>

                    <label for="service">Choose a Service:</label><br>
                    <select id="service" name="service" required>
                        <option value="">-- Select --</option>
                        <option value="web-design">Web Design</option>
                        <option value="seo">SEO Optimization</option>
                        <option value="maintenance">Maintenance</option>
                    </select><br><br>

                    <label>Preferred Contact Method:</label><br>
                    <input type="radio" id="contact-email" name="contact_method" value="email" required>
                    <label for="contact-email">Email</label><br>
                    <input type="radio" id="contact-phone" name="contact_method" value="phone">
                    <label for="contact-phone">Phone</label><br><br>
                </fieldset>

                <fieldset>
                    <legend>Additional Information</legend>
                    <label for="comments">Comments:</label><br>
                    <textarea id="comments" name="comments" placeholder="Your message..." rows="4" cols="40"></textarea><br><br>

                    <label>
                        <input type="checkbox" name="subscribe" value="yes">
                        Subscribe to our newsletter
                    </label><br><br>

                    <label for="readonly-info">Promo Code (Read-Only):</label><br>
                    <input type="text" id="readonly-info" name="promo" value="WELCOME2025" readonly><br><br>
                </fieldset>

                <input type="submit" value="Submit Form">
                <input type="reset" value="Reset Form">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 PLP week 2. All rights reserved.</p>
    </footer>

</body>
</html>n JavaScript.

## Instructions

Design a simple multi-section web page that showcases the use of lists, tables, and media, followed by a complete HTML5 form. The page should reflect thoughtful structure, usability, and clarity.

Your form should include various input types, make use of labels and fieldsets for accessibility, and apply HTML5 validation rules through attributes like `required`, `type`, `minlength`, `pattern`, and others.

Avoid using JavaScript for validation—rely solely on native HTML5 capabilities.

## Deliverables

Submit a single HTML file named `enhanced-form.html`. It should include:

* Well-structured content using lists, tables, and media.
* A complete HTML5 form including a variety of input fields.
* Correct use of form attributes such as `placeholder`, `required`, `autocomplete`, and `readonly`.
* HTML5 validation features implemented correctly across all relevant fields.
* A clear, accessible layout using semantic tags.

## Tips

* Proper and meaningful use of lists, tables, and media.
* Clarity and accessibility of form structure.
* Correct use of form elements and attributes.
* Effective application of native HTML5 validation.
* Clean, well-indented, and maintainable HTML code.


