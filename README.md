# Ascent Physiotherapy Website Redesign Project

## DGL103 HTML/CSS - Final Project | [North Island College](https://www.nic.bc.ca/)

### Site chosen to redesign and build
[https://ascentphysiotherapy.com/](https://ascentphysiotherapy.com/)

---

### What is the most important purpose of this website?

The purpose of the Ascent Physiotherapy website is to provide information about the clinic's physiotherapy services, highlighting its specialties and professional team. It aims to attract potential patients by showcasing the facilities, emphasizing expertise, and making it easy to schedule appointments, particularly with the free consultation offer. The site also builds trust and credibility by presenting the professional team and a welcoming environment.

---

### Who is the target audience?

- **Primary Audience**: Individuals in the Comox Valley region looking for physiotherapy services focused on recovery, pain management, and physical rehabilitation.
- **Secondary Audiences**:
  - **Sports and Active Patients**: Athletes or active individuals needing injury rehabilitation or performance enhancement.
  - **Older Adults**: People requiring mobility treatments or ongoing care to improve quality of life.
  - **Professional Referrals**: Doctors or specialists who may refer patients to Ascent Physiotherapy.

---

### What is the overall message, and what actions do we want the audience to take?

- **Main Message**: Ascent Physiotherapy is a trustworthy, professional clinic dedicated to restoring mobility, reducing pain, and improving physical well-being through personalized, effective treatments.
- **Primary Action**: Encourage users to schedule a free consultation or make direct contact.
- **Secondary Actions**: Instill confidence in visitors so they feel they are in good hands, motivating future visits or referrals.

---

### Current Site Issues

#### Accessibility:
- **Alt Text**: Missing on images, affecting usability for screen reader users.
- **Font and Contrast**: The font size and color contrast may not meet accessibility standards, making it harder for users with visual impairments to navigate.
- **Navigation Structure**: Lack of optimized ARIA roles and labels may make it challenging for users with disabilities to navigate.
- **Language Identifier**: Missing `lang` attribute in HTML, which is essential for screen readers and assistive technologies.

#### Speed:
- **Image Optimization**: Large, unoptimized images slow down loading times.

#### Design:
- **Outdated Visual Style**: The overall design might feel outdated, lacking a clean, modern look.
- **Visual Hierarchy**: Important information may not stand out enough.
- **Inconsistent Branding**: Inconsistent design elements create a disjointed user experience.

#### Content:
- **Limited Information on Services and Team**: Lack of detail on team qualifications and service descriptions limits the site’s authority.
- **Unclear Calls-to-Action (CTAs)**: CTAs are not clear or prominently displayed.

#### Responsiveness:
- **Poor Mobile Adaptation**: The site may not be fully optimized for mobile, impacting usability on smaller screens.
- **Layout Shifts**: Elements may not adapt smoothly across devices, disrupting navigation.

---

### Redesign Approach

#### Visual Mood
Calm and minimalist with a warm, approachable feel. The design should be clean and professional, focusing on empathy and recovery to inspire trust.

#### Inspiration
1. [Clinica Talus](https://www.clinicatalus.cl/)
![Clinica Talus](https://cdn.discordapp.com/attachments/218940816582901760/1306081497060610059/image.png?ex=67355eae&is=67340d2e&hm=4b7c67638185b8e15883f03e6880e7211b57241a756b0527821165be6fb0469f&)
2. [Hinge Health](https://www.hingehealth.com/)
![Hinge Health](https://cdn.discordapp.com/attachments/218940816582901760/1306081496678793309/image.png?ex=67355eae&is=67340d2e&hm=0c2a13ca505134023d3d633d6c777b8f1f5973dd676dabf6a26343507b054ad5&)
#### Colors
- **Primary**: Dark Green (`#1C5F5F`) - Used in key sections and elements that draw the user's attention to important actions, aligning with the theme of health and wellness to convey trust and professionalism.
- **Neutral**: Light bluish-gray (`#DCE6E7`) - Used as a background in various content sections, creating a welcoming and clean atmosphere that allows the content to stand out without visual overload.
- **Text/Main Typography**: Black (`#000000`) - Applied in headings, main text, and elements requiring clarity and readability, maintaining consistency with the brand’s logo.

#### Fonts
- **Headlines**: Montserrat - a modern, professional sans-serif.
- **Body Copy**: Open Sans - a versatile sans-serif enhancing readability.

---

### Website Structure

#### Home Page

- **Header**
  - Logo
  - Main Navigation: 
	  - Home
	  - Our Services
	  - Our Team
	  - Facilities & Success Stories
	  - Make an Appointment (Contact)

- **Hero Section**
  - Heading: "Restore your Well-being and Return to Your Best Self"
  - Paragraph: Description of Ascent Physiotherapy
  - Image: Team members
  - No link here

- **Free Consultation Section**
  - Call to Action: Free consultation & more services
  - Images: Services overview
  - Statistics: Recovery rate, satisfaction, rehabilitation patients

- **Expert Team Section**
  - Heading: "Expert Team"
  - Image: Team
  - Paragraph: Description of the team
  - List of 4 main options to choose us:
	-   Experienced and knowledgeable therapists.
    -   Customized rehabilitation program.
    -   modern and comfortable facilities.
    -   proven success in patient recovery.
  - Call to Action: "Free Consultation"

- **Experience Physiotherapy Section**
  - Heading: "Experience the Full Potential of Physiotherapy"
  - Paragraph: Description of therapy at Ascent
  - Image: Physiotherapy equipment
  - List of 4 Therapy Cards: 
	  - Each Card Includes: 
		  - Therapy Heading
		  - Therapy Description
		  - Link to Detailed Product & Services Page

- **Testimonials**
  - Heading: "Hear it from Our Patients"
  - Paragraph: Description to join us
  - List of 3 Testimonial Cards**: 
	  - Each Card Includes: 
		  - Rating Stars
		  - Comments
		  - Patient Image
		  - Patient Name
		  - Patient Job
  - Link: "See Testimonial"

- **Call to Action**
	- Logo
	- Link to Call us
	- Paragraph with phone number
	- Link to Visit us
	- Paragraph with address facility

- **Footer**
  - Navigation: 
	  - Home
	  - Our Services
	  - Our Team
	  - Facilities & Success Stories
	  - Make an Appointment (Contact)
  - External Links: 
	  - WorkSafeBC
	  - GGIMS
	  - College of Physical Therapists of BC
	  - Contact Form: Request information
  - Copyright
  - Education Purposes: “Created for educational purposes”

---

#### Our Services Page

- **Header**: Same as on the Home Page
- **Services Section**
  - Heading1: "Our Services"
  - Heading2: "Conditions We Can Handle"
  - Paragraph: Descriptions of conditions section
  - List of 6 Condition Cards: 
	  - Each Card Includes: 
		  - Icon Related to Condition
		  - Condition Name
		  - Type of Therapy
		  - Therapy Method
  - No link here

- **Pain-Free Future Section**
  - Heading: "Pain-Free Future"
  - Paragraph: Invitation to a future free from pain
  - Image: Description of pain free points
  - Call to Action: "Free Consultation"

- **Prices Table Section**
  - Pricing Table: Service types and prices
- **Call to action**: Same as on the Home Page
- **Footer**: Same as on the Home Page

---

#### Our Team Page

- **Header**: Same as on the Home Page
- **Our Team Section**
  - Heading1: "Our Team"
  - Heading2: "Meet Our Specialists"
  - No link here
  - List of 8 Specialist Cards: 
	  - Each Card Includes: 
		  - Specialist Image
		  - Specialist Name
		  - Specialty 
		  - Hover shows Description of the Specialist

- **Expert Section**: Same as on Home Page
- **Call to action**: Same as on the Home Page
- **Footer**: Same as on the Home Page

---

#### Facilities & Success Stories Page

- **Header**: Same as on the Home Page
- **Facility Section**
  - Heading1: "Facilities & Success Stories"
  - Heading2: "Our Facility"
  - Video of facility
  - No link here

- **Spaces & Equipment Section** 
	- Heading: "Spaces & Equipment"
	- No link here	
	- List of 4 Space Cards: 
	  - Each Card Includes: 
		  - Space Image
		  - Space Name
 
- **Testimonials Section**: Same as on Home Page
- **Call to action**: Same as on the Home Page
- **Footer**: Same as on the Home Page

---

#### Make an Appointment Page

- **Header**: Same as on the Home Page
- **Get in Touch Section**
  - Heading1: "Make an Appointment"
  - Heading2: “Get in touch”
  - Paragraph: "Description of contact and more information
  - List of 3 Contact Cards: 
	  - Each Card Includes: 
		  - Icon
		  - Contact Text (phone, email, address)
		  - Contact Detail (phone number or email address)
  - Follow Us: Social Icons
  - Contact Form
  - Google Map: Clinic location

- **Call to action**: Same as on the Home Page
- **Footer**: Same as on the Home Page

---

### Educational Use Notice

This project is created solely for educational purposes. The redesign serves as a practical learning experience in web design and development.

---

