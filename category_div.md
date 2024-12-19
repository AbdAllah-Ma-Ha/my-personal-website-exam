### <section> main(home):
     -<div> (navbar)
            <nav>elements of navbar</nav>
     -<div> (main-container) ***flex***
            <div> (left-content)
                    contains elemements of about-left
            <div>(right-content)
                    contains img of about-right

### <section> about:
     -div(container-about)
         -div(about-flex)***flex***
             -div(about-left)
                 contains elements of about-left
             -div(about-right)  
                 contains img of about-right

### <section> skills:
     -div(container-skills)
         --div(skills-content)
            -p(skills-title)

            --div(skill-item)*6
               -p(skill-name)
               --div(progress)
                  -div(progress-fill)
                     -p(progress-fill)

### <section> projects:
     -div(container-projects)
         --div(section-project-title)
            -p(section-project-title)

         --div(projects-flex)
            --div(project)*3
               -i(project-icon)
               -p(title-project)
               -p(description-project)
               -a(link-project)

### <section> contact:
     -div(contact-container)
         --div(contact-flex)
            --div(section-contact-title)
               -p(contact-title)

            --div(contact-fields)
               -form
                  -input(contact-input)
                  -input(contact-input)
                  - textarea(contact-textarea)
                  -button(btn-primary)
                  -p(contact-message)
                  --div(contact-socials)
                     -a(social-link)
                     -a(social-link)
                     ---a(social-link)
                     
