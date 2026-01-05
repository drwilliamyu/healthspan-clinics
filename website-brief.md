Hi, please use Markdown in your communications where possible.


**Purpose**

Public-facing website for a new healthcare service led by an endocrinologist.  
The site must communicate clinical credibility, define scope clearly, and support compliant patient engagement.

**Clinical Scope (must be reflected accurately)**
- Specialist endocrinology:
    - Diabetes
    - Thyroid
    - Obesity
    - Pituitary
    - Adrenal
        
- Healthspan positioning (approved language only):
    
    > Healthspan care focuses on identifying and managing endocrine and metabolic risk factors that influence function and wellbeing as we age, using evidence-based medicine within established clinical guidelines.
    

No outcome guarantees, longevity claims, or comparative superiority language.

**Core Infrastructure**
- content management system: Wordpress or Webflow only
- hosting: Australian-based servers only
- third-party integration: Hotdoc for real-time booking requests
- include analytics tools
- additional: chatbot for user support/lead capture - direct query to backend user (receptionist)

**Technical Performance**
- optimise for 2 seconds for Largest Contentful Paint
- serve all images as `.webp` with lazy loading
- provide and guide SEO: implement MedicalBusiness markup

**UX/Functional Design**
- Mobile-first & responsive web design
- Burger-menu with `position: sticky;` top-right on scrolling
- In mobile, have a footer with `position: fixed;` that has methods of contact (see https://ascension.com.au/ in mobile view)
- Custom elements:
	- Searchbar for Patient Hub
	- Searchbar for Clinician Resources
	- Ability for me to integrate my own custom calculators

**Other**
- Provide a privacy policy page
- Cookie consent banner; compliance with Australian Privacy Principles
- High-contrast option/button
- Include medical disclaimer
- Include keyboard navigation

**Colour Palette**
["#244040","#BDDBD0","#AFC1D6","#8B687F","#F2A654"]

Use `#F2A654` for CTA buttons

**Sitemap**

  - path: /
    title: Home

  - path: /healthspan
    title: Healthspan & Longevity

  - path: /about
    title: The Clinic
    children:
      - path: /about/process
        title: Our Process
      - path: /about/clinicians
        title: Our Clinicians

  - path: /resources
    title: Resources
    children:
      - path: /resources/patient-hub
        title: Patient Hub
      - path: /resources/clinician-resources
        title: Clinician Resources
      - path: /resources/calculators
        title: Calculators

  - path: /contact
    title: Contact Us


**Placeholder Contact/Locations**

34 Morley Avenue, Rosebery, NSW 2018

+61 (2) XXXX XXXX

hello@healthspanclinics.com.au
