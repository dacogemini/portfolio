# Glossary of frontend terms

Table of Contents: [0-9] (# 0-9) [A] (# a) [B] (# b) [C] (# c) [D] (# d) [E] (# e) [F ] (# f) [G] (# g) [H] (# h) [I] (# i) J [K] (# k) [L] (# l) [M] (# m) [N ] (# n) [O] (# o) [P] (# p) [Q] (# q) [R] (# r) [S] (# s) [T] (# t) [U] (#u) [V] (# v) [W] (# w) XYZ

## 0-9

### 9-slice scaling
** 9-fold scaling ** (non-distorting scaling), a technique that allows you to change the size of an object without geometric distortion. The object is divided into 9 shares (3 lines and 3 columns), each of which is scaled according to its own rules: the corners do not scale at all, the central share is scaled in height and width, the remaining shares are scaled either only in width or only in height.

## A

### accessibility, a11y

** accessibility, ** ability to use the interface by all, regardless of physical or technical limitations.

### adaptive design

** adaptive design, ** approach to the design of sites, taking into account their adaptation to various devices and conditions, is opposed to the common "fixed" design only for computers. One of the ways to create responsive design is the method of [responsive design] (# responsive-design).

### almost standards mode

** almost standard mode, ** browser mode of interpreting and displaying the page, in which the browser purposefully moves away from standards (as in [compatibility mode] (# quirks-mode)) only for certain special cases, is used for pages with transitional [doctypes] (#doctype) HTML 4 and XHTML 1.

### anchor

1. ** link, ** hyperlink between two documents.
2. ** anchor, ** link to an element within a document, may be part of a hyperlink.

### animation

** animation, ** smooth change of visual parameters of the object.

### asset

** resource, ** component of the site: text files, graphics, video, databases, etc. In the narrow sense “static resource”: styles, scripts, design graphics, as opposed to dynamic [content] (https: // github. com / web-standards-ru / dictionary / blob / master / dictionary.md # content).

### assert

** check, ** condition that is checked, used in testing, ex. _field assert has failed - the field check failed ._

### at-keyword

** directive key, ** see [directive] (# at-rule)

### at-rule

** directive, ** [declaration] type (# statement) starting with `@` sign, for example. _ @ import_.

### attribute

** attribute ** ex. `rel =" stylesheet "`.

- attribute name - ** attribute name **
- attribute value - ** attribute value **

## B

### back-end

** back **

1. the area of ​​web technologies running on the server.
2. The internal part of the server system, is engaged in data processing.

### background

** background, ** ex. _background image - background image._

 - background-color - ** background color **
 - background-position - ** background position **
 - background-size - ** background size **
 - background-repeat - ** background repeat **
 - background-origin - ** background borders **
 - background-clip - ** background cropping **
 - background-attachment - ** pin background **
 - background-image - ** background image **

### baseline

** baseline, ** an imaginary line at the base of the letters in a line.

### bikeshed

** pay excessive attention to detail, ** (see [the law of triviality] (https://ru.wikipedia.org/wiki/Zakon_trivialnosti)). There is no settled Russian equivalent; when translating, it is better to convey a general meaning, for example. _avoid bikeshedding - do not argue about trifles_.

### blending mode

** blending mode, ** layer blending algorithm used in graphic editors or directly in CSS, for example. _overlay blending mode - overlay blending mode._

### block

1. ** block of declarations, ** the structural part of the [declaration] (# statement). It is enclosed in curly braces and contains declarations of properties (or, in the case of media expressions, style blocks).
2. ** block view, ** see [view] (# display)

### blockquote

** block quote, ** HTML element to highlight a quoted document area. May contain the attribute `cite` with reference to the source.

### border

** frame, ** external visible part of the block, for example. _border-left - the frame on the left._

- border-collapse - frame merging
- border-color - border color
- border-image - graphic frame
- border-image-outset - the protrusion of the graphic frame
- border-image-repeat - repeating the graphic frame
- border-image-slice - graphic frame breakdown
- border-image-source - the address of the image for the graphic frame
- border-image-width - thickness of the graphic frame
- border-radius - rounding the frame
- border-style - frame style
- border-width - the width of the frame

### border-radius

** frame rounding, ** eg, _border-radius: 3px - rounding the frame by 3 pixels, border-top-left-radius - rounding the upper left corner, _ see also [rounded corners] (# rounded-corners).

### bounding box

** bordering block **

### box model

** block model, ** block dimension system, consists of content, indent, frame, and outer indent.

### box-shadow

** shadow (block), ** ex. _box-shadow is red - block shadow is red ._

### breadcrumbs

** bread crumbs, ** auxiliary navigation on the site, consistently reflecting the structure or steps taken.

### breakpoint

1. ** breakpoint, ** line in code where script execution pauses to invoke the debugger.
2. ** control point, ** condition under which the layout of the site changes from one to another. Characteristic for media expressions.

### browser

**browser**

### button

**button**

1. an interface element that, when clicked, sends a form or performs another action
2. form element `<button>` or `<input type =" button ">` (also `submit` and` image`).

## C

### callback

** Callback, ** Execution of the code upon completion of the function, for example. _pass value in a callback - pass the value in the callback._

### candidate recommendation (CR)

** candidate for recommendation, ** specification status [W3C] (# world-wide-web-consortium-w3c), one of the possible options for [proposed recommendation] (# proposed-recommendation-pr).

### cascade

** cascade, ** scheme described in the CSS specification, which determines the order of applying the style blocks to an element, depending on their source, importance, [specificity] (# specificity) and position in the code. The erroneous “cascade” is sometimes called the [child selector] (# selector).

### cell

**cell**

1. structural unit of the table.
2. an element of the table `<td>` or `<th>`.

### cellpadding

** indent in cells ** tables.

### cellspacing

** distance between cells ** tables.

### character reference

** character substitution, ** ex. `& nbsp;`. Suppose also not quite accurate, but more well-established translation ** special character. **

### checkbox

** checkbox **

1. interface element to select one or more options, for example. _checkbox is disabled - the checkbox is inactive ._
2. form element `<input type =" checkbox ">`.

### child

1. n ** descendant, ** (in mn. h. children - ** descendants **)
2. adj. ** child **, for example. _child process_ - _daughter process_

### classitis

** Classical, ** Fictional disease, which is characterized by excessive use of multiple classes: both for registration and for information storage.

### clear

** undo wrapping, ** CSS property that prohibits a block from wrapping previous floating blocks.

- clear: left - ** cancel wrapping on the left **
- clear: right - ** undo wrapping right **
- clear: both - ** undo wrapping on both sides **

### clearfix

** kliarfiks, ** reception to prevent collapsing containers with floating blocks. It consists in the creation of a special strut, which is located after the floating blocks and cancels their wrapping. A special case of solving problems with floats (see [summary table of all problems and solutions] (http://css-live.ru/articles-css/clearfix-block-formatting-context-methods-cheatsheet.html)).

### click

** click, ** click on an object using a mouse cursor or similar device, for example. _double click is firing event - double-clicking causes an event.

### client-side

** Client side, ** The field of browser-based technologies is often synonymous with [frontend] (# front-end).

### clipping path

** contour trim **

### closure

** closure, ** function containing in the body references to variables declared in the surrounding code.

### code

1. n ** code ** non-numeric (like sugar), for example. _error in code - an error in the code, _ but not a _error in the codes_ (wrong).
2. Ch. ** write code, typeset, program, ** ex. _to code a site - to impose a site._

### colspan

** join columns, ** HTML attribute to join several table cells in one row.

### column

** column, column, ** vertical area in a table, layout, or text.

### color

**Colour**

### combinator

** combinator, ** special character used in a complex selector to precisely specify a combination of DOM elements, for example. `>`, `+` and others. The space between selectors is also considered a combinator.

- descendant combinator - ** descendant combinator, ** `` (space).
- child combinator - ** combinator of the immediate descendant, ** `>`. Also called ** child **.
- adjacent sibling combinator - ** the immediate neighborhood combinator, ** `+`.
- general sibling combinator - ** neighborhood combinator, ** `~ ~.

### comment

** comment ** clarification to the code

### component

** component **, (m. r.) part of something. For example _app components_ - application _components_

### compositing

** compositing **

### composite layer

** composite layer **

### compositor

** composer ** (meaning “compositing engine”)

### content

**content**

- metadata content - ** meta content **
- flow content - ** stream content **
- sectioning content - ** structural content **
- heading content - ** heading content **
- phrasing content - ** text content **
- embedded content - ** embedded content **
- interactive content - ** interactive content **
- palpable content - ** content for output **
- script-supporting content - ** script content **
- grouping content - ** grouping content **

### continuous integration

** continuous integration **, the practice of frequent, automated assembly, testing and deployment of software

### cross-browser

** cross-browser, ** running in all browsers, together.

### cross-platform

** cross platform, ** working on all platforms, together.

### CSS Working Group (CSSWG)

** CSS Working Group **

### custom

** custom ** (optional ** custom **)

- custom element - ** custom element **.
- custom attribute - ** custom attribute **.

## D

### data binding

** data binding, ** automatic data synchronization between two entities, usually a model and a view.

### declaration

** declaration, ** property and value declaration.

### deep comparison

** deep comparison, ** comparison of two objects, this compares the structure of objects and verifies the equality of the primitives contained within the objects.

### deploy, deployment

** deploy, deployment, layout, roll-out, ** publication of changes either directly to the public server (production), or through intermediate systems and processes of automatic assembly.

### design

1. n ** design, ** the visual appearance of the site, may include the principles of interaction and architectural solutions, for example. _new design for a site - a new design for the site_.
2. Ch. ** develop, ** create or design a look and functionality.

### device pixel ratio

see [pixel ratio] (# pixel-ratio)

### dirty checking

** checking for "dirty" properties of an object **, that is, [deep comparison] (# deep-comparison) of model properties, which results in [callback] (# callback) if something has changed.

### disable

** deactivate **

### disabled

** inactive, ** state of a form element in which its modification is prohibited, for example. _disabled button - inactive button._

### display

1. ** view **, css-property that determines the type of display block.

	- display: none - ** hidden view **
	- display: block - ** block view **
	- display: inline - ** line view **
	- display: inline-block - ** type of line block **
  - display: flex - ** view of the flex container ** (see [flexbox] (# flexbox))
  - display: inline-flex - ** type of line flex container ** (see [flexbox] (# flexbox))

2. ** screen **, for example. _screen smartphone, screen resolution_.

### divitis

** Divatoz, ** Fictional disease, which is characterized by the use of only elements `<div>` instead of [semantically] (# semantics) suitable.

### DOM

** document object model, house **

### doctype

** doktayp, ** construction of the form `<DOCTYPE html>` at the beginning of the document, which indicates the version of HTML used. Used by browsers to select a mode ([standard] (# standards-mode-standards-compliance-mode), [almost standard] (# almost-standards-mode) or [compatibility] (# quirks-mode)).

### dropdown

** drop-down menu, ** interface element that reveals additional information when activated.

## E

### easing

** smoothness, smoothness function, ** describes how to change the animation speed using keywords or Bezier curves, for example. _transition easing is linear - smooth transition linear._

### editor's draft (ED)

** editorial draft, ** early status of the [W3C] specification (# world-wide-web-consortium-w3c) proposed by one of the editors. Based on the editorial draft, a [working draft] (# working-draft-wd) can be compiled.

### element

**element**

- void elements - ** empty elements **
- raw text elements - ** elements with free text **
- escapable raw text elements - ** elements with screened free text **
- foreign elements - ** third-party elements **
- normal elements - ** ordinary elements **

### em

** eat, ** unit of measurement in CSS, which depends on the font size of the parent, for example. _font-size: 3em - font size 3 ema._

### enable

**activate**

### enabled

** active, ** state of the form element in which its change is allowed, for example. _enabled button - the active button._

### engine

** engine ** for example _Safari is based on WebKit engine - Safari powered by Webkit engine._

## F

### fallback

** Folback, ** Backup, Additional implementation in case the browser does not have the necessary features, such as the included scripts or the necessary video codecs, for example. _fallback to a link - send a link to the link._

### favicon

** Favicom, ** Website icon, usually 16 × 16 pixels in ICO format.

### feature query

** directive `@ suppórts`, ** conventional design, which allows selectively applying styles depending on browser support of certain properties and values. There is no direct established translation following the example of [media expressions] (# media-query).

### fieldset

** group of fields, ** an element that combines several form fields, for example. _green border on a fieldset - a green frame on a group of fields._

### figure

** shape ** element from HTML5, containing an image, video, table, graph or code snippet.

### figcaption

** caption of the figure, ** title or caption of the figure.

### filter

**filter**

 - filter: brightness - ** brightness **
 - filter: contrast - ** contrast **
 - filter: grayscale - ** colorless **
 - filter: sepia - ** sepia **
 - filter: invert - ** inversion **
 - filter: saturate - ** saturation **
 - filter: hue-rotate - ** turn colors **
 - filter: blur - ** blur **
 - filter: opacity - ** opacity **
 - filter: drop-shadow - ** shadow **
 
### flash of ...

 - flash of unstyled text, FOUT - ** flashing text without styles **, displaying text in the system font before loading the web font
 - flash of invisible text, FOIT - ** flickering of invisible text **, the lack of text on the page before downloading the web font
 - flash of faux text, FOFT - ** flickering of synthesized text **, displaying text outlines in a modified main font before loading the necessary fonts

### flexbox

** flexbox, ** mechanism [layouts] (# layout).

 - flex container - ** flex container **
 - flex item - ** flex element **
 - flex-direction - ** main axis direction **
 - flex-wrap - ** transfer of flex-elements **, determines whether the container is single-line or multi-line
 - flex-basis - ** base size ** of the flex element along the main axis
 - flex-grow - ** stretch ratio **
 - flex-shrink - ** compression ratio **
 - main axis - ** main axis **, the direction in which the flex elements follow each other in the container
 - cross axis - ** transverse axis **, direction perpendicular to the main axis
 - main size - ** main size **, size of the flex element along the main axis
 - cross size - ** cross size **, size of the flex element along the transverse axis
 - justify-content - ** distribution of flex-elements ** along the main axis
 - align-items - ** alignment of flex-elements ** along the transverse axis
 - align-self - ** alignment of the flex element ** along the transverse axis
 - align-content - ** align the lines ** of the container along the transverse axis
 - order - ** serial number ** of the flex element

### float

1. app. ** floating, ** block property, forcing subsequent blocks to flow around it, ex. _float layout - layout on floating blocks._
2. Ch. ** wrap around, ** follow close to the floating unit, for example. _text is floating to the right - the text wraps around the right._
3. Ch. ** press, ** rest against the right or left, usually due to floating properties, ex. _float block to the left - push the block to the left._

### font

**font**

- font-weight - ** saturation **

	- font-weight: normal - ** normal **
	- font-weight: bold - ** bold ** or ** bold ** (in typographic tradition)
	- font-weight: bolder - ** fatter **
	- font-weight: lighter - ** lighter **

- font-style - ** font style **

	- font-style: normal - ** straight **
	- font-style: italic - ** course **
	- font-style: oblique - ** oblique **

- font-size - ** font size, size **

- font-family - ** font family, typeface **

	- font-family: serif - ** with serif **
	- font-family: sans-serif - ** sans serif **
	- font-family: monospace - ** monospace **

### footer

**basement**

1. characteristic visual area at the end of the page.
2. The element `<footer>` is a semantic part with meta-information.

### formatting context

** formatting context **, in CSS - an area in which the visual elements of the page (text fragments, blocks, cells, etc.) are lined up according to certain rules.

- block formatting context, BFC - ** block formatting context **, ** BKF ** (eg _element with `overflow` establishes the new BFC - the element with ʻoveflow` creates a new BKF_)
- grid formatting context - ** grid formatting context ** (see [grid layout] (# grid-layout))
- flexbox formatting context - ** flexbox formatting context ** (see [flexbox] (# flexbox))
- inline formatting context - ** line formatting context **
- table formatting context - ** table formatting context **

### fragment identifier

** fragment identifier, ** text after `#` in the URL, allowing you to refer to a specific part of the document. Used mainly in specifications and when working with SVG, the more familiar term [anchor] (# anchor) is used in HTML.

### framework

** framework, ** a set of libraries and components to simplify development. As a rule, is the basic frame of the product. _Napr., [Twitter Bootstrap] (http://getbootstrap.com/) ._

### front-end

** frontend **

1. The area of ​​technology for the development of web interfaces, includes supporting tools and technologies running in the browser or [client-side] (# client-side).
2. The external part of the server system, which is responsible for receiving data, sending responses and generating code for the browser, is included in the [server] (# server-side).

### full screen

** full-screen mode, ** the behavior of the program or its part, in which it occupies the entire screen.

### function

**function**

1. in programming, a named fragment of program code (subroutine) that can be accessed from another place in the program.
2. in CSS - may be present in the [declaration] (# declaration) on the value position. For example, `url (img / gradient.png)`.

## G

### generated content

** generated content, ** part of a document created using CSS, [pseudo-element] (# pseudo-element) and the `content` property.

### graceful degradation

** gradual degradation ** - an approach in which the interface of the site degrades for older browsers, where some of the technologies used are not supported. At the same time, the damage to the user is mitigated whenever possible. For example: the color of the substrate instead of the gradient, raster graphics instead of vector graphics, video playback using a plugin. There is also a more literal translation of _ "elegant degradation" _.

### gradient

** degrees, ** smooth transition from one color to another.

- linear gradient - ** linear gradient **
- radial gradient - ** radial gradient **
- conical gradient - ** conical gradient **

### grid

1. ** grid, ** a way to arrange the arrangement of elements in a design using a vertical or horizontal rhythm, for example. _module grid - modular grid._
2. ** grid **, two-dimensional grid of rows and columns in [grid layout] (# grid-layout).

### ** grid layout **
** grid layout, ** mechanism [layouts] (# layout), allowing to place elements on a two-dimensional grid - [grid] (# grid) (2).

- ** grid container ** - * grid container *
- ** grid item ** - * grid item *
- ** grid track ** - * grid band *, a collective term for rows and columns * grid *
- ** grid cell ** - * grid cell *
- ** grid line ** - * grid-line *, virtual border between adjacent * grid-bands *, to which you can attach * grid-elements *
- ** grid area ** - * grid-area *, space to accommodate * grid-elements *, bounded by four * grid lines *
- ** grid gutter ** - * grid spacing *, the gap between adjacent * grid bands *


## H

### header

**cap**

1. characteristic visual area at the beginning of the page.
2. The element `<header>` is the semantic title part.

### height

**height**

## I

### icon font

** iconic font, ** synthetic font containing icons and other flat vector images for website design, for example. _build an icon font - compile the icon font ._

### immutable

** immutable, ** the term is most often applied to data (data types) in functional programming.

### implement

** implement, implement ** ex. _Firefox has been implemented support of everything - Firefox has implemented support for everything ._

### inline

1. ** lower case, ** having lower case properties.

	- inline block - ** line block **.
	- inline box - ** line element ** in line formatting: part of filling the container of the line to which the CSS rules are directly applied, for example. _anonymous inline box is an anonymous line element_.
	- inline element - ** line element **.

2. ** built-in, ** located inside the line of code.

	- inline styles - ** inline styles **.
	- inline SVG - ** embedded SVG **.
	- inline script - ** built-in script **.

### input

** form element, ** providing user interaction with the interface, for example: text field, button, switch.

### interoperability

** interoperability **

## K

### kerning

** kerning, ** distance between pairs of letters, taking into account their shape for a more uniform set.

### keyframe

** keyframe, ** one of the specified points of the animation, changes between which occur automatically.

### keyframe animation

** frame animation, ** way to set animation in CSS using keyframes.

### keyword

**keyword**

## L

### label

** label, ** establishes a connection between a specific element and a form element.

### last call (LC)

** last draft, ** specification [W3C] status (# world-wide-web-consortium-w3c) for recent revisions before [candidate recommendation] status (# candidate-recommendation-cr) _ (canceled in 2014, is found only in old specifications) _.

### layout

** layout, ** the location of the main blocks on the page, for example. _3 columns layout - layout in 3 columns._

### legend

** legend, ** the header of a group of form elements, is determined using the [field group] (# fieldset)

### length

**length**

### letter-spacing

** Letter spacing, tracking, ** The total spacing between letters in the text is different from [kerning] (# kerning).

### library

** library **, a set of ready-made solutions to simplify development. As a rule, the library implements some specific function or set of related functions, for example, animation.

### line-box

** line container ** in line formatting: a virtual container containing all elements of a single line.

### line-height

** line height, leading, ** the distance between the base lines of the text.

### list

** list, ** sequential enumeration of a group of elements.

- ordered list - ** ordered list, ** sorted according to some principle.
- unordered list - ** unordered list, ** in which the order does not matter.

### list-style

** list style **

## M

### margin

** external indent, ** ex. _margin-bottom: -10px - lower negative indent 10 pixels ._

### margin box

** external indents of smth. **

### matrix

** matrix (transformation), ** description of the transformation of the object using the matrix.

### media query

** media output, ** declaration of the `@ media` directive with certain [conditions] (# media-query-list), allows to apply styles depending on the device capabilities. The translation option “media queries” reflects the essence of the work less accurately.

### media query list

** conditions of media expression, ** list of conditions that determine when the ads within the directive `@ media` will be applied. For example, `only screen and (min-width: 35em)`.

### media type

** device type, ** can be a media expression condition. Specifies what type of output the styles are intended for (eg `screen` to screen,` print` to print, `speech` to speech synthesizer).

### media feature

** device characteristics, ** can be a condition of media expression. Defines the characteristics of the device. For example, `min-width`.

### mixin

** impurity, ** a set of properties that extends the behavior of another entity is found in CSS preprocessors and JavaScript patterns, for example. _mixin is clearing - the impurity clears the stream ._

### mobile first

** First mobile, ** development approach, in which the design of the service begins with the mobile version, and not with the version for large screens. The term was introduced by Luke Wroblewski in [the book of the same name] (https://abookapart.com/products/mobile-first).

### mock object

** dummy object **

### mock-up

** Layout, ** Appearance or design of the site of varying degrees of detail, for example. _designer has sent a page mock-up - the designer has sent a page layout._

### modal

1. app. ** modular, ** blocking interface for performing some action, for example. _modal dialog - modal dialog._
2. n ** modal window (dialog), ** interface element, see _modalnyy__

### multiple

** multiple, ** repeated two or more times, for example. _multiple backgrounds - multiple backgrounds ._

### multiple columns

1. ** multicolines, ** a mechanism from CSS that allows to build text in several columns, for example. _multiple columns support in IE - multicolumn support in IE._ Preferably than bulky “multiple columns”.
2. ** multi-column, ** consisting of several columns, for example. _multiple columns layout - multi-column layout._

## N

### nested

** nested, ** inside something, ex. _double nesting - double nesting._

### node

** node, ** structure element, for example. _child node is a child node._

### number

** number, numeric type **

## O

### opacity

** opacity, ** degree of opacity, ex. _opacity: 0.1 - opacity 10% ._ Often mistakenly called transparency.

### opaque

** opaque, ** degree of opacity, ex. _opaque by 75% - 75% opaque, _ means 25% transparency.

### outline

** stroke, ** outer uniform contour of the element, not participating in the block model.

## P

### package manager

** package manager, ** less commonly ** package manager, ** assistive software for managing the installation, configuration, upgrade, and removal of software components.

### padding

** internal indent, ** ex. _padding-top: 10px - upper inner indent 10 pixels ._

### pagination

1. ** paginated navigation, ** usually a list of links with the number of pages into which the document is broken.
2. ** pagination, ** dividing a document into separate pages for ease of reading, downloading, or other purposes.

### pattern

** patter, ** formalized approach to writing code, for example. _JavaScript patterns - javascript patterns

### parent

**parent**

### percentage

** percentage, percent **

### performance

** speed, ** characteristic of download speed, drawing, etc., for example. _CSS performance - CSS performance._

### performance budget

** budget for performance, ** maximum allowable performance indicators for a web application. Going beyond such a budget means a slowdown in performance. For example _Performance Budget Metrics - performance budget indicators._

### persistent data structures

** permanent data structures **

### pinch

** flattening (dilution) of fingers, ** gesture to control the touch interface: flattening (depending on the direction - breeding) of fingers on the touch screen.

### pixel

** pixel, ** unit of measure for screen design, in pl. ** pixels, ** abbr. **PC.**

- physical pixel - ** physical pixel, ** cell on the matrix, unit resolution of the device display.
- device independent pixel (dip) - ** virtual pixel, ** device-independent pixel, can be more, less or equal to the physical.
- bitmap pixel - ** raster pixel **.

### pixel density

** pixel density, ** number of pixels that fit in a linear screen size unit, for example. The pixel density of the screen is 326 pixels per inch.

### pixel ratio

** pixel ratio, ** ratio of physical pixel to virtual, for example. _screen has pixel ratio of 2 - the pixel ratio of the screen is 2._

### placeholder

1. ** stub, ** temporary substitute for images, text, etc. For example: _In place of the portrait of the president, insert the plug with the cats for the time being_.
2. ** field hint, ** text field attribute, is intended for a hint on how to fill this field. Most often is an example of filling. Eg: `placeholder =" + 7 (999) 123-12-13 "`.

### ppi (pixel per inch)

** ppi ** unit of pixel density (see [pixel density] (# pixel density)).

### plugin

** TODO **

### polyfill

** polyfile, ** script, recreating the missing functionality, for example. _new polyfill for IE6 - new polyfill for IE6._

### progressive web metrics

** progressive web metrics; ** set of metrics pages related to [speed] (# performance).

- first paint - ** first draw **
- first contentful paint - ** first significant drawing **
- first meaningful paint - ** first significant drawing **
- visually ready - ** visual readiness **
- visually complete - ** visual completion **
- first interactive - ** first interactivity **
- estimated input latency - ** expected input delay **
- time to first interactive - ** time before the first interactivity **
- time to first consistently interactive - ** time before the start of stable interactivity **

### prolyfill

** Prolifil, ** One of the variants [Polyfil] (# polyfill), characterized in that it reproduces the _probable_ functionality described in the specification, but not yet implemented in browsers.

### popup

** pop-up window, popup, ** a separate window or interface element that appears on top of the current one, for example. _annoying popup - annoying popup._

### position

** positioning **

- position: static - ** static **
- position: absolute - ** absolute **
- position: relative - ** relative **
- position: fixed - ** fixed **
- position: sticky - ** fixed **

### preprocessor

** preprocessor, ** tool that converts code from one syntax to another, for example. _Sass CSS preprocessor - CSS preprocessor Sass._

### progress bar

** progress bar, ** interface element, showing the progress of the operation.

### progressive enhancement

** progressive improvement ** - an approach in which all browsers get the same basic functionality, but in modern browsers this functionality is expanded in accordance with the support of new technologies. For example: gradients, vector graphics, video playback.

### Progressive Web App, PWA

** progressive web application, ** - an approach to developing web applications that combines the advantages of regular websites and native applications: fast download, installation in the OS, work offline, push notifications, access to system APIs. Installation information is described in the web manifest. The progressiveness of the approach is that in a regular browser it’s just a website, and in supporting browsers and OS it’s an application.

### promises

** promis, ** asynchronous execution of scripts, opposed to using callbacks.

### property

** property, ** ex. _CSS-property_.

### proposed recommendation (PR)

** proposed recommendation, ** specification status [W3C] (# world-wide-web-consortium-w3c), probable candidate for [recommendation] (# recommendation-rec).

### pseudo-element

** pseudo-element, ** an additional internal element created using CSS and `:: before` or` :: after`.

### pseudo-class

** pseudo-class, ** used to bind a declaration to a specific state of a DOM element. Separated from the selector with a colon sign `:`. For example, the rule block declaration with the `.item: hover` selector is applied when the cursor is positioned on` .item`.

### pull request, pr

** pullrequest, ** request to accept changes to a repository branch from a fork or another branch.

## Q

### quirks mode

** compatibility mode, ** browser interpretation and display page, in which the browser purposefully moves away from the standards in order to display documents created before the beginning of the 2000s. and relying on errors and features of browsers of the time. Used for pages without [doctype] (# doctype) and with outdated doctypes (eg. HTML 3.2).

## R

### radio button

** radio window, ** form element `<input type =" radio ">` to select one of several options, for example. _radio button is checked - the radio button is selected._

### recalculate

** recalculation **

### recommendation (REC)

** recommendation, ** final status of the [W3C] specification (# world-wide-web-consortium-w3c) recommended for implementation in browsers and for use by developers.

### reflow

** repackage **

### rem

** rem, ** unit of measurement in CSS, which depends on the font size of the root element `<html>`, for example. _font-size: 3rem - font size 3 rem ._

### render

** drawing **

### repaint

** redraw **

### reset

** reset, ** usually reset the default styles in CSS, ex. _style reset file - style reset file._

### resolution

** resolution, ** the number of physical pixels on the device screen, for example. _screen resolution is 1024 × 768 pixels - the screen resolution is 1024 × 768 pixels ._

### responsive design

** responsive design, ** one of the technological methods of creating [adaptive design] (# adaptive-design).

### Responsive Images Community Group (RICG)

** Community Team on Adaptive Images **

### rest parameters

** residual parameters, ** (also _the remaining parameters_, colloquially _rest-parameters_) syntax in JavaScript, which allows to represent unnamed parameters of the function as an array.

### root

**root**

### rounded corners

** rounded corners, ** ex. _rounded corners are out of fashion - rounded corners are out of fashion, _ see also [rounding the frame] (# border-radius).

### row

** row, row **

- horizontal area in the table or layout.
- table element `<tr>`.

### rowspan

** merge rows, ** HTML attribute to merge multiple table cells in one column.

### rule-set

** element style block **, consists of a selector (or media expression) and a block of declarations.

## S

### shallow comparison

** superficial comparison, ** comparison, in which it is checked whether two variables refer to the same object in memory.

### scaffolding

** scofolding, ** automatic code generation by description, metaprogramming method.

### scale

1. n **scale**
2. Ch. **to scale**

### scope

** scope, ** limited part of the program structure in which the declared variable is available, or the `<style scoped>` styles are applied.

### script

** script, ** instructions describing the behavior of pages, for example. _scripts are not loaded yet - the scripts have not loaded yet ._

### scroll

1. ** scrolling, ** interface element to move a hidden part of a page or block, is a sign that the nested element is larger than its parent, for example. _horizontal scroll is disabled - horizontal scrolling is disabled ._
2. ** scroll, ** move the hidden part of the page or block.

### scrollbar

** scroll bar, ** formal name [scroll] (# scroll), for example. _system scrollbars - system scrollbars ._

### sectioning roots

** structural fundamentals **

### semantics

** semantics, ** semantic load of HTML elements, for example. _semantic coding - semantic layout ._

### selector

** selector, ** necessary structural part of [style block] (# rule-set). Responsible for binding declarations to DOM elements.

- simple selector - ** simple selector, ** can be [pseudo-class] (# pseudo-class) or one of the following types:
    - type selector - ** selector by type, ** refers to the tag, for example. `ul`,` input`, etc.
    - universal selector - ** universal selector, ** asterisk: `*`.
    - ID selector - ** selector by identifier, ** ex. `# content`.
    - class selector - ** class selector, ** ex. `.item`.
    - attribute selector - ** attribute selector, ** ex. `[type = submit]`.
- compound selector (other sequence of simple selectors) - ** compound selector **, a chain of simple selectors that are not separated by combinators, for example. `input [type = submit]: focus`.
- complex selector - ** complex selector **, several simple and / or compound selectors separated by combinators:
    - descendant selector - ** child selector **, for example. `ul li`.
    - child selector - ** immediate descendant selector **, for example. `#buttons> *`. Also often referred to as ** child **.
    - adjacent sibling selector - ** immediate neighborhood selector **, for example. `.item + .item`. Also often referred to as ** neighbor **.
    - general sibling selector - ** neighborhood selector **, for example. `.item ~ .item`.

### server-side

** serverside, ** the area of ​​technologies working on the server is often a synonym for [backend] (# back-end).

### shadow DOM

** shadow dom, shadow document model **

### shapes

** shapes, CSS shapes **

### shared

1. app. ** shared **, for example. _shared memory - shared memory_
2. adj. ** general **, for example. _shared folder - shared folder_, _shared access - shared_

### shim

** pwm, ** code that helps unify browsing, usually implements the missing or normalizes existing support, for example. _HTML5 shim for IE8 - HTML5-shim for IE8._

### sibling

** neighbor ** (meaning “neighboring element”).

### sidebar

** sidebar, ** side of the site with secondary content, for example. _sidebar is on the right side - there is a side panel on the right._

### skew

1. n **incline**
2. Ch. **cant**

### source maps

** code maps, ** special markup that allows you to align the source files and compiled code for debugging.

### specification, spec

** specification, ** technology documentation for developers and browser vendors, usually in one of the statuses: from proposed to approved by W3C, for example. _specification draft - draft specification ._

### spread

** extension **, an operator in JavaScript that extends expressions in those places where several arguments are used when calling `doSomething (... array)` functions, several elements are expected in arrays `[1, 2, ... array] `) and add or rewrite fields in the objects` {... object, field: 'value'} `.

### specificity

** specificity, ** characteristic [CSS selector] (# selector), defining its priority [in cascade] (# cascade). It consists of the weight of each [simple selector] (# selector) in its composition.

### stacking context
** context overlay, ** an element of the page's visual structure, limiting the effect of the `z-index` property of its descendants and placed along the _z_ axis as a whole (either entirely over or entirely under any other element). For example _elements with opacity create new stacking context - elements with translucency form a new context overlay._

### staging server

** debug server ** server where the product is tested and debugged.

### standards mode, standards compliance mode

** standard mode, ** mode of interpretation and display of the page by the browser, in which the browser is obliged to comply with the standards as fully as possible. Used for pages with more or less modern [doctype], for example. doctype HTML5.

### statement

** declaration **, CSS structural element. This could be an element style block, an import directive, a media expression, etc.

### string

1. ** string type, ** in programming, a data type whose values ​​are an arbitrary sequence (string) of characters in the alphabet.
2. ** string, ** in CSS - the string value of a directive or property. For example, in `content:" \ 201d "` the string is `" \ 201d "`.

### stub object

** stub **

### style

1. n ** styles, ** ex. _apply styles to an element - apply styles to the element, _ pl. preferable: _style element, _ rather than _style element_ (wrong).
2. Ch. ** make out, ** ex. _how to style selects - how to make selects, _ rather than ambiguous "stylize".

### style guide

** style guide, ** ex. _project code style guide - project code style guide_.

### stylesheet

** style sheet, ** ex. Table of document styles.

### swipe

** swipe, ** gesture to control the touch interface: brushing fingers across the touch screen.

### submit

** shipping, ** ex. _ form submit_.

## T

### tab

1. ** tab, ** one of the layers of the interface of the site or program, which is activated by selecting its title, for example. _open in new tab - open in a new tab._
2. ** tab, ** tab key, inserts a tab character, switches focus to the next interface element, or complements a partially typed word, for example. _press Ctrl Tab - click control-tab._
3. ** tab, ** tab character, has a custom width and is used for indentation in the code, for example. _tabs are better than spaces - tabs are better than spaces ._

### tag

1. ** tag, ** element designation in HTML, there are opening, closing and single tags. For example _ closing tag is missing - closing tag is missing._
	- tag name - ** tag name **
	- start tag - ** opening tag **
	- end tag - ** closing tag **
2. ** label, ** content marker, usually a short word.

### tap

** press, ** gesture to control the touch interface: touch the touch screen once.

### text

**text**

### textarea

** text area, ** form element for entering multiline text.

### text-align

** alignment, off, ** orientation of text lines in a certain direction, or evenly across the width of the block.

- text-align: left - ** left **
- text-align: right - ** right **
- text-align: justify - ** in width **

### text-shadow

** shadow (text) ** ex. _text-shadow is red - the text shadow is red ._

### throttling

** trotting, ** introducing artificial restrictions, for example, to reduce the frequency of calls to event handlers in JavaScript or the network speed and CPU power during testing.

### thumb

1. Abbreviation for [thumbnail].
2. ** slider, ** control element [scrollbar] (# scrollbar).

### thumbnail

** thumbnail, ** thumbnail image.

### title

1. ** title, ** if we are talking about the element <<>> `, or the title of the element.
2. ** hint, ** if we are talking about the attribute `title =" "`.

### toggle

** switch, ** translate from one state to another, _switch classes - toggle classes._

### tooltip

** tooltip, ** supporting information that appears when you hover over an item or when it is activated, in particular `title =" "`.

### touch interface

** touch interface **

### transform

** transformation, ** ex. _transform: scale (2) - transformation by scaling 2 times ._

### transition

** transition, ** ex. _transition: all 2s linear - linear transition of 2 seconds duration._

### translate

** move, ** move an object using CSS transformation, for example. _translate (x, y) - move to X and Y._

### transpiler

** transpiler, ** compiler that converts source code in one language. programming in source code in another language programming.

### typography

** typography, ** text layout using headset selection, line options and more.

## U

### unit

** unit of change, ** ex. _rem unit - the unit of measurement "rem" ._

### unit testing

** unit testing **

### URI

** uniform resource identifier, ** character sequence identifying an abstract or physical resource.

### URL

1. ___ ** address **. The value is recommended for use when translating articles.

2. ** uniform resource locator, ** [URI] (# URI), which also provides information about the location of this resource, for example. _background: url ("http://www.example.com/picture.png") _

### user experience (UX)

** user experience, ** set of sensations from interacting with smth. (interface, device, product). In the context of the field of knowledge, it is recommended to use the abbreviation UX (for example, _UX-specialist_).

### user interface (UI)

** user interface, ** in a transparent context, it is recommended to use just an “interface”.

### utility

** utility ** program with a narrow purpose.

## V

### valid

** valid, ** conforming to a standard, specification or other standard, for example. _valid markup - valid markup_.

### validator

** validator, ** means of verifying compliance with a standard, specification, or other standard (see [valid] (# valid)), for example. _W3C markup validator - W3C_ markup validator.

### value

** value, ** ex. _value CSS properties_.

### vendor prefix

** Browser prefix, ** Prefix to the CSS property `-webkit-` or `-moz-`, for example. _add vendor prefixes - add browser prefixes._

### vendor files

** third-party files, ** styles, scripts and other resources (dependencies) of other authors used in the project, for example. _tons of vendos scripts included in the code - a bunch of third-party scripts are connected in code._

### vertical-align

** vertical alignment, ** the vertical position of elements within a line of text or a table.

### viewport

** viewport **

1. visible area of ​​the document within the screen.
2. the element `<meta name =" viewport ">`, which controls the adaptation of pages on mobile devices.

## W

### website, web site

** website ** united under one page address, translation of the “website” is redundant.

### worker

** worker **, an interface in javascript that allows the script to run not in the main thread.

- web worker - ** web worker **
- service worker - ** service worker **
- shared worker - ** shared worker **

### working draft (WD)

** working draft, ** early status of specification [W3C] (# world-wide-web-consortium-w3c).

### worklet

** wormlet **, a class in JavaScript that has previously known methods with a specific signature that gives access to various browser-based APIs. [Project Houdini] (https://github.com/w3c/css-houdini-drafts/wiki) provides the following types of worklets:

- paint worklet - ** drawing render **
- compositor worklet - ** compositing workshop **
- layout worklet - ** layout workout **

### World Wide Web Consortium (W3C)

** World Wide Web Consortium, ** web standards development organization. To translate "web" as a "web" in the XXI century is already ridiculous.

### web standards

** web standards **

### width

**width**

### word-spacing

** word break **

### workaround

** workaround (reception), ** a way to solve a problem in limited conditions, for example. _to figure out workaround - come up with a workaround._
