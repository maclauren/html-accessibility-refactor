## html-accessibility-refactor

## Code Refactor README

#### Deployed link: 

#### Description:

#### Table of Contents:
1. User Story
2. Acceptance Criteria
3. Method
    * Semantic HTML elements
    * Logical structure
    * Images and icons, accessible alt attributes
    * Heading attributes
    * Title elements title

#### 1. User Story
AS A marketing agency. I WANT a codebase that follows accessibility standards. SO THAT our own site is optimized for search engines.

#### 2. Acceptance Criteria
- Semantic HTML elements can be found throughout the source code
- HTML elements follow a logical structure independent of styling and positioning
- Image and icon elements contain accessible alt attributes
- Heading attributes fall in sequential order
- Title elements contain a concise, descriptive title

#### 3. Method

Semantic HTML elements

- Changed <div> for navigation to <div id="nav">
- Changed <div class="header"> to <header class="header">
- Changed <div class="hero"> to <figure class="hero">
- Changed <div class="content"> to <section class="content">
- Changed <div class="benefits"> to <aside class="benefits">
- Changed <div class="footer"> to <footer class="footer">
- Changed <div class="search-engine-optimization"> to <div id="search-engine-optimization" class="search-engine-optimization"> so the link would navigate to the correct section
- Changed <div id="search-engine-optimization" class="search-engine-optimization"> to <nav id="search-engine-optimization" class="search-engine-optimization">
- Did the same for the other two navigation links
- Changed <div class="benefit-lead"> to <article class="benefit-lead">

Logical structure

???

Images and icons, accessible alt attributes

- Added alt attributes to the three images on the page using this template https://www.w3schools.com/tags/att_img_alt.asp
- Added alt attributes to the three icons on the page using this template https://www.w3schools.com/tags/att_img_alt.asp
- Removed </img> tag after the third icon img tag and replaced with /> to make the same as the previous two icons for consistency
- Removed redundant space at the end of img tags


