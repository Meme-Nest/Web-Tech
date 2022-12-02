<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Form in HTML](#form-in-html)
  - [Form Elements/ Fields](#form-elements-fields)
  - [Text Box](#text-box)
    - [Pattern](#pattern)
  - [Email Box](#email-box)
  - [Password Box](#password-box)
  - [Number Box](#number-box)
  - [Checkbox](#checkbox)
  - [Calender / Calender Box](#calender--calender-box)
    - [Min Max format](#min-max-format)
  - [Dropdown Box / Select Box](#dropdown-box--select-box)
  - [Radio Button](#radio-button)
  - [Reset Button](#reset-button)
  - [File Button/ Upload Button](#file-button-upload-button)
  - [TextArea Box](#textarea-box)
  - [Range Box](#range-box)
  - [Submit Button](#submit-button)
  - [Color Box](#color-box)
  - [time box](#time-box)
  - [Date and Time box](#date-and-time-box)
  - [Fieldset](#fieldset)
  - [Legend](#legend)
  - [Iframe](#iframe)
    - [assignment :](#assignment-)
  - [Web Browser:](#web-browser)
  - [Web Application:](#web-application)
  - [Webpage:](#webpage)
  - [WebElement:](#webelement)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Form in HTML

## Form Elements/ Fields

![](img/Form%20Elements.PNG)
![](img/Form%20Elements2.PNG)
![](img/Form%20Elements3.PNG)

---

## Text Box

1.  Input tag is used to create textbox in the webpage.
1.  In the input tag we have specify the value of the "type" attribute as "text", o create the text box.
1.  "placeholder" attribute is used to add the placeholder to the text box or any field which is created using \<input>.
1.  "required" attribute is used to make the text box input as compulsory.
1.  "pattern" attribute is used to do the validation of the field based on the given pattern.
1.  "title" attribute is used to display the warning message based on the "pattern" attribute

#### Example I

---

<form>
   <h4>Text Box</h4>
   <label>Name</label>
   <input type="text" placeholder="First Name">
   <input type="submit">
</form>

---

#### Example II

---

<form>
   <h4>Text Box</h4>
   <label>Name</label>
   <input 
   type="text" 
   placeholder="First Name" 
   required 
   >
   <input type="submit">
</form>

---

#### Example III

---

### Pattern

- [ ] => Characters or number
- {min,max} => min and max count
- \- => one or more condition
- ^ => match the beginning
- $ => match the end

  ### Phone Number

  1.  Must be 10 digits
  1.  1<sup>st</sup> digit must be within 6 tag and the remaining 9 digit must be within in 0-9.

      ```
      "^[6-9]{9}[0-9]{9}$"
      ```

  ### example

  ```html
  <form>
    <h4>Text Box</h4>
    <label>Name</label>
    <input
      type="text"
      placeholder="First Name"
      required
      pattern="[a-zA-Z]{5,13}"
    />
    <input type="submit" />
  </form>
  <!-- phone form -->
  <form>
    <h4>Text Box : Phone Number</h4>
    <label>Ph no. : </label>
    <input
      type="text"
      placeholder="First Name"
      required
      pattern="^[6-9]{1}[0-9]{9}$"
      title="Invalid Phone Number"
    />
    <input type="submit" />
  </form>
  ```

   <form>
      <h4>Text Box</h4>
      <label>Name</label>
      <input 
      type="text" 
      placeholder="First Name" 
      required 
      pattern="[a-zA-Z]{5,13}"
      >
      <input type="submit">
   </form>
   <form>
      <h4>Text Box</h4>
      <label>Ph no. : </label>
      <input 
      type="text" 
      placeholder="First Name" 
      required 
      pattern="[6-9]{1}[0-9]{9}"
      >
      <input type="submit">
   </form>

  ***

## Email Box

<form>
   <h4>Email Box</h4>
   <label>Email : </label>
   <input 
   type="email" 
   placeholder="abc@email.com" 
   required
   >
   <input type="submit">
</form>

---

## Password Box

---

<form>
   <h4>Password Box</h4>
   <label>Password : </label>
   <input 
   type="password" 
   placeholder="" 
   required
   >
   <input type="submit">
</form>

---

## Number Box

---

<form>
   <h4>Number Box</h4>
   <label>Age : </label>
   <input type="number"  min="18" max="60"  >
   <input type="submit">
</form>

- The up arrow of the spin control in the number box will start from 1.
- The down arrow of the spin control in the number box will start from -1.
- "min" attribute is used to set the minimum count in the number box."max" attribute is used to set maximum count in the number box. spin control will set the min and max value based on the min and max attribute.
- "step" attribute is used to set the step count or incrementing and decrementing count in the number box. By default step will be 1 for incrementing and -1 for decrementing.

#### Step attribute

---

   <form>
   <h4>Number Box</h4>
   <label>Age : </label>
   <input type="number"  min="18" max="60"  step=3>
   <input type="submit">
   </form>

---

## Checkbox

---

<form>
   <h4>Checkbox</h4>
   <input type="Checkbox"><label>Java</label>
   <input type="Checkbox"><label>C</label>
   <input type="Checkbox"><label>Python</label>
   <input type="submit">
</form>

---

## Calender / Calender Box

- In the input tag "type" attribute must be specified as "date" to create "calender box" in the form.
- By default calender box will display the date in dd-mm-yyyy format.
- Using "mint' and "max" attribute we can set the minimum and maximum dates to be displayed in the calender.
- While specifying the value for min and max attribute "yyyy-mm-dd" format must be used.

```html
<input type="date" />
```

<input type="date">

### Min Max format

```html
"yyyy-mm-dd"
```

- example
  ```html
  <input type="date" min="1999-01-01" max="2010-01-01" />
  ```
  <input type="date" min="1999-01-01" max="2010-01-01">

---

## Dropdown Box / Select Box

```html
<form>
  <h4>Select Country:</h4>
  <label>Country</label>
  <select>
    <option>Select</option>
    <option>India</option>
    <option>Japan</option>
    <option>UK</option>
    <option>USA</option>
  </select>
  <input type="submit" />
</form>
```

<form>
<h4>Select Country: </h4>
<label>Country</label>
<select >
<option >Select</option>
<option >India</option>
<option >Japan</option>
<option >UK</option>
<option >USA</option>
</select>
<input type="submit">
</form>

---

## Radio Button

- In the input tag "type" attribute must be specified as "radio" for creating the radio button.

- While creating the radio button "name" attribute must be same for all the radio buttons such that it will allow us to select only one radio button at a time.

<form>
<input type="radio" name="gender"><label>Male</label>
<input type="radio" name="gender"><label>Female</label>
<input type="radio" name="gender"><label>Other</label>
<input type="reset"> 
<input type="submit">
</form>

---

## Reset Button

- Reset button will reset all the form value to default/ initial values.
- In the input tag type attribute must be specified with "rest" to create the rest button.

```html
<form>
  <input type="text" placeholder="name" />
  <input type="reset" />
</form>
```

<form>
<input type="text" placeholder="name">
<input type="reset">
</form>

---

## File Button/ Upload Button

- In the input tag type attribute should be specified as 'file' to create the upload button

```html
<form>
  <input type="file" placeholder="name" />
  <input type="reset" />
</form>
```

<form>
<input type="file" placeholder="name">
<input type="reset">
</form>

## TextArea Box

- \<textarea> tag is used to create textarea in the web.
- textarea can be used for writing the comments or address etc.
- we can add a paragraph in a textarea. Textarea can be resized.

```html
<form>
  <textarea rows="4" cols="50">This is a TextArea</textarea>
  <br />
  <input type="reset" />
  <input type="submit" />
</form>
```

<form>
<textarea rows="4" cols="50">
This is a TextArea
</textarea>
<br>
<input type="reset">
<input type="submit">
</form>
## Search Box

<input type="search">

## Range Box

```html
<form>
  <input type="range" />
</form>
```

<form>
  <input type="range"/>
</form>

## Submit Button

```html
<form>
  <input type="text" placeholder="name" />
  <input type="submit" />
</form>
```

<form>
<input type="text" placeholder="name">
<input type="submit">
</form>

## Color Box

```html
<form>
  <input type="color" />
  <input type="submit" />
</form>
```

<form>
  <input type="color" />
  <input type="submit" />
</form>

## time box

```html
<form>
  <input type="time" />
</form>
```

<form>
<input type="time">
</form>

## Date and Time box

```html
<form>
  <input type="datetime-local" />
</form>
```

<form>
<input type="datetime-local">
</form>

## Fieldset

## Legend

## Iframe

- iframe tag is used to add or embed eternal source in owr webpage.
- by default iframe will have the border,
  - remove border using
    - frameborder="no" and
    - scrolling="no"
  - set size using attributes
    - height and
    - width

```html
<iframe
  src="https://png.pngtree.com/background/20210712/original/pngtree-neon-double-color-futuristic-frame-colorful-background-picture-image_1178693.jpg"
  hight="300"
  width="500"
>
</iframe>
```

<iframe
  src="https://png.pngtree.com/background/20210712/original/pngtree-neon-double-color-futuristic-frame-colorful-background-picture-image_1178693.jpg" 
  hight="300"
  width="500"
> 
</iframe>

### assignment :

- iframe assignment : historical place
  - image of place
  - map

## Web Browser:

Web browser is a platform where we can access the web applications. eg: chrome, firefox, IE, safari, opera.

## Web Application:

Web Application is a collection of different webpages. WebApplication is made up of 3 layers i.e. front-end, back-end
and the database. Eg: amazon.com, flipkart.com etc

## Webpage:

Webpage is a page which is viewed in the browser. Every webpage is designed using HTML. Collection of webpages
forms a web application.

## WebElement:

Every elements or the contents in the webpage is a WebElement. A Webpage is a collection of different WebElements.
