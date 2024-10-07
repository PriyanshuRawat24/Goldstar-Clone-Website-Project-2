# digilikers-project-2
 
HTML


1. Document declaration (basic information):

<!DOCTYPE html>: This line declares the document type as HTML.
<html lang="en">: This line specifies that the document language is English.

 2. Head Section:

This section contains information about the web page that is not displayed directly on the browser.
<meta charset="UTF-8">: Defines the character encoding standard used for the text content.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: This line sets the viewport to ensure proper responsiveness on different devices.
You've linked various external resources using <link> tags:
Bootstrap CSS framework for styling (href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css")
Swiper library for sliders (href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css")
Font Awesome icons (href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css")
OwlCarousel library for carousels (href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css")
<title>home-page</title>: Sets the title of the webpage displayed on the browser tab.

3. Body Section:

This section contains the visible content of the webpage.

Navbar Section:

It includes a logo (<img src="./img/nav-logo.png" alt="Logo">) and navigation links.

Banner Carousel Section:

It uses Bootstrap's carousel component to display a banner that likely uses an image (./img/banner.jpg).

About Us Section:

It displays information about the company, including a company description, an image (./img/about-us.png), and a button to learn more.

Our Service Section:

It showcases the company's services with heading text and multiple cards. Each card contains an icon (./img/our-service-logo-1.png, etc.), a heading, and a description.

Video Section:

It displays a video (./img/video.mp4) within a container.

Background Image for Home Service Section:

It includes a background image (background-image-home-service-wrapper).

Home Service Section:

It promotes the company's home service with a heading, a button, and a paragraph describing the benefits.

Feature Product Section:

It highlights the company's featured products with a heading ("Feature product").
It showcases VRLA batteries for solar applications with an explanation and an accordion component to display additional details about the product's advantages.

The accordion component uses Bootstrap's accordion functionality to allow users to expand and collapse sections for more information.
It also showcases another featured product (likely MF Battery for Solar Application) but the description content is cut off in the provided code.

Overall, this HTML file provides a well-structured foundation for a website homepage. It incorporates various design elements and functionalities to showcase the company's information, services, and products

CSS

Global Styles:

html, body: Sets the margin, padding, font family, overflow, and scroll behavior for the entire webpage.

Navbar Styles:

.nav-bar-wrapper: Sets the background color of the navigation bar wrapper.
.navbar: Sets the background color, color, display, justification, alignment, and padding for the navigation bar.
.navbar .nav-logo: Styles the logo within the navigation bar with color, font size, and text decoration.
.navbar ul: Styles the unordered list of navigation links with margin, padding, display, and margin-right.
.navbar ul li: Sets the margin-left for each list item.
.navbar ul li a: Styles the anchor links within the list items with color, text decoration, font size, and text transformation.
.nav-logo: Styles the logo container with display and alignment.
.nav-logo img: Styles the logo image within the container with width and height.
About Section Styles:

.about-wrapper: Sets the margin-top for the about section.
.about-heading-box: Styles the heading text within the about section.
.about-para-box p: Styles the paragraph text within the about section.
.button-box button: Styles the button within the about section with border, background color, text transform, color, margin, and padding.

Our Services Styles:

.our-service-wrapper: Sets the margin-top, padding, and background color for the our services section.
.our-service-heading-box: Styles the heading text within the our services section.
.box-card: Styles the card containers for each service with margin, text-align, background color, and border.
.inner-logo-box-card img: Styles the logo image within each card.
.inner-text-box-card: Styles the text within each card.

Video Section Styles:

.video-wrapper: Sets the text-align and margin-top for the video section.

Background Home Service Section Styles:

.background-image-home-service-wrapper: Sets the background image, background position, background repeat, background attachment, and padding for the background image section.

Home Service Section Styles:

.home-service-wrapper-section: Sets the display and justify-content for the home service section wrapper.
.home-service-wrapper: Sets the width, margin-top, background color, and border for the home service section.
.home-service-head-box: Styles the heading text within the home service section.
.home-service-para-box p: Styles the paragraph text within the home service section.

Feature Section Styles:

.feature-wrapper: Sets the margin-top and padding for the feature section.
.feature-heading-text-box h3: Styles the heading text within the feature section.
.feature-text-box-1, .feature-text-box-2, .feature-text-box-3: Styles the text boxes within the feature section.
.feature-img-box-1 img: Styles the image within the feature section.
.feature-img-box img: Styles the image within the feature section.

Our Projects Styles:

.our-project-wrapper: Sets the margin-top, padding, and background color for the our projects section.
.our-project-heading-box: Styles the heading text within the our projects section.
.our-project-image-box-1, .our-project-image-box-2, .our-project-image-box-3: Styles the image boxes within the our projects section.

Our Blog Article Styles:

.our-blog-article-wrapper: Sets the margin-top and padding for the our blog article section.
.our-blog-article-head-box h4: Styles the heading text within the our blog article section.
.our-blog-article-img-box: Styles the image box within the our blog article section.
.our-blog-article-img-box img: Styles the image within the our blog article section.
.our-blog-article-text-box: Styles the text box within the our blog article section.
.our-blog-article-text-box h5: Styles the heading text within the our blog article section.
.our-blog-article-text-box h4: Styles the heading text within the our blog article section.
.button-box-blog-box button: Styles the button within the our blog article section.

Footer Styles:

.footer-wrapper: Sets the background color for the footer.
.footer-image-box img: Styles the image within the footer.
.footer-logo-box: Styles the logo box within the footer.
.footer-logo-box ul: Styles the unordered list of logos within the footer.
.footer-logo-box li: Styles the list items within the logo list.
.quick-links-box h5: Styles the heading text within the quick links section.
.quick-links-inner a: Styles the anchor links within the quick links section.
.quick-links-inner li: Styles the list items within the quick links section.
.product-box: Styles the product box within the footer.
.product-box h5: Styles the heading text within the product box.
.product-inner a: Styles the anchor links within the product box.
.product-inner li: Styles the list items within the product box.
.form-box: Styles the form box within the footer.

About Page Styles:

.discover-Our-journey-wrapper: Sets the background color and padding for the discover our journey section.
.discover-Our-journey-heading-box: Styles the heading text within the discover our journey section.
.discover-Our-journey-para-img-box: Styles the paragraph and image box within the discover our journey section.
.discover-Our-journey-para-box: Styles the paragraph text within the discover our journey section.
.discover-Our-journey-img-box img: Styles the image within the discover our journey section.
.section-entry: Sets the padding for the section entry.
.about-background-wrapper: Sets the background image, background repeat, background size, background attachment, and padding for the about background section.
.about-background-heading-box: Styles the heading text within the about background section.
.make-better-wrapper: Sets the margin-top for the make better section.
.make-better-img-box img: Styles the image within the make better section.
.make-better-para-box: Styles the paragraph text within the make better section.
.Ahead-of-Others-wrapper: Sets the margin-top and margin-bottom for the ahead of others section.
.Ahead-of-Others-heading-box: Styles the heading text within the ahead of others section.
.feature-text-box h3: Styles the heading text within the ahead of others section.
.feature-text-box p: Styles the paragraph text within the ahead of others section.
.accordion: Sets the margin-top for the accordion.
.Ahead-of-Others-img-box: Styles the image box within the ahead of others section.

Contact Page Styles:

.contact-info-wrapper: Sets the margin-top for the contact info wrapper.
.contact-info-main-box-1, .contact-info-main-box-2, .contact-info-main-box-3, .contact-info-main-box-4: Styles the background image for the contact info boxes.
.contact-info-logo-box: Styles the logo box within the contact info section.
.contact-info-text-box: Styles the text box within the contact info section.
.contact-form-img-box: Styles the image box within the contact form section.
.contact-form-para-box: Styles the paragraph text within the contact form section.
.contact-button-box button: Styles the button within the contact form section.


Service Center Styles:

.service-center-wrapper: Sets the margin-top, margin-bottom, padding-bottom, and background color for the service center wrapper.
.service-center-logo-para-box: Styles the logo and paragraph box within the service center section.
.service-center-para-box: Styles the paragraph text within the service center section.
.service-center-logo-box: Styles the logo box within the service center section.
.service-center-logo-box a: Styles the anchor link within the service center section.
.service-center-img-box: Styles the image box within the service center section.

Javascript

null





