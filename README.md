# Portfolio
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Survey Form</title>
  </head>

  <body>
    <h1 id="title">
      Papa's Foods Feedback Form
      </h1>

      <p id="description">
        Thank you for dinning with us today! Please provide feedback on your dining experince.
      </p>

      <form id="survey-form">
        <fieldset>
<legend>Personal Information</legend>
        <label id="name-label" for="name">Name (required):</label>

        <input
        placeholder="e.g., John Doe"
        required 
        id="name"
         type="text">

<label id="email-label" for="email"> Email (required):</label>

<input
placeholder="example@email.com"
required
id="email" 
type="email">

<label id="number-label" for="number">Number (optional):</label>

<input
placeholder="555-555-5555"
id="number" 
type="number"
min="1"
max="1000">
</fieldset>

<fieldset>

<legend>Did you enjoy the customer service?</legend>

<input 
id="yes-option" 
value="yes" 
name="customer-service" 
type="radio">

<label for="yes-option">Yes</label>

<input
id="no-option"
value="no"
name="customer-service"
type="radio">

<label for="no-option">No</label>
</fieldset>

<fieldset>

  <legend>How did you hear about us?</legend>

  <input 
  type="checkbox"
  id="community"
  name="choice"
  value="community">

  <label for="community">Your Community</label>

<input
type="checkbox"
id="social"
name="choice"
value="social">

<label for="social">Social Media Platforms</label>

<input
type="checkbox"
id="reputation"
name="choice"
value="reputation">

<label for="reputation">Reputation</label>

  </fieldset>

</fieldset>

<fieldset>

<legend>Rating</legend>

<label for="dropdown">How was the food?</label>

<select name="dropdown" id="dropdown">

<option  value="bad">Bad</option>

<option value="good">Good</option>
</select>

  </fieldset>
<label for="more-feedback">Any more Feedback for us?</label>
  <textarea 
  id="more-feedback" name="more-feedback"
  cols="30" rows="10">
    </textarea>
<button id="submit">Submit Form</button>
        </form>
  </body>
</html>
