# Creative Theme

This is my version of  a customised the hugo creative theme 

# Additional Features

* Contact Form
* Social Netoworking buttons in contact form
* Scoll down feature in layouts

# Installation
$cd <themes_directory>
$git clone https://github.com/kamalim/creative-x
$hugo -t creative-x

# Configuration

For the new feature contact form here is the configure needed in the config.toml file

    # Contact section
    [params.contact]
        headline = "Let's Get In Touch!"
        description = "Ready to start your next project with me? That's great! Write to me and I will get back to you as soon as possible!"
        email = ""
        buttonText = "Send message"

        # 'warning' defines error messages for invalid inputs
        [params.contact.form.name]
            text = "Your Name *"
            warning = "Please enter your name."

        [params.contact.form.email]
            text = "Your Email *"
            warning = "Please enter your email address."

        [params.contact.form.phone]
            text = "Your Phone *"
            warning = "Please enter your phone number."

        [params.contact.form.message]
            text = "Your Message *"
            warning = "Please enter a message."

        [[params.contact.social]]
            icon = "fa-linkedin-square"
            link = "your linkedin profile link" 

        [[params.contact.social]]
            icon = "fa-twitter-square"
            link = "your twitter profile name"

        [[params.contact.social]]
            icon = "fa-skype"
            link = "skype link"

        [[params.contact.social]]
            icon = "fa-slideshare"
            link = "slideshare link"

        



# Attribution

Largely adapted from the official [hugo creative theme](http://themes.gohugo.io/creative/) 

## License

This theme is released under the Apache License 2.0 For more information read the [license](https://github.com/kamalim/creative-x/blob/master/LICENSE).





