# MAGIC 8 BALL
Allow the user to ask a question. Return a random response from the magic 8-ball.

## SPECIFICATIONS
  * Your HTML page should include a text input to allow the user to ask a question and a submit button.

  * When the user types a question and clicks submit, you will randomly return a response from "The Magic 8-Ball"

  Here are some possible responses, but be creative with it:

      - I think that it will work out!
      - Maybe... maybe not
      - Probably not
      - Highly likely
      - It is certain!
      - I don't know about that
      - My sources say no

  * Display The Magic 8-Balls response to the user. Be creative with how you display the response.

  * After *N* seconds, remove The Magic 8-Balls response, clear the input field, and allow the user to ask a new question.

## EXTRA CREDIT
  * Add basic client-side validation to the text input to ensure that the user has not left the field blank and that the input ends with a question mark.

  * Try using promises to ask The Magic 8-Ball a question and then reset the response after *N* seconds. An example of this type of promise chaining might look like:

      ```javascript
      // Handle user input
      const handleSubmit = () => {
        // Prevent the form from being submitted
        event.preventDefault();

        // Ask "The Magic 8-Ball" a question
        ask(input.value)
          // If there are no errors, it will return a random message.
          // We can display that response and set a timeout to be resolved in 5 seconds
          .then(msg => displayResponse(msg, 5))

          // When the promise resolves, call the resetReponse function
          .then(resetResponse)

          // If the promise is rejected, we know there is an error that needs to
          // be displayed. So display the error.
          .catch(err => displayError(err));
      };

      // Listen for click events on the submit button
      submitBtn.addEventListener('click', handleSubmit, false);
      ```

## EXAMPLE
[Here is an example](https://codepen.io/tophergates/full/dVmOXL/) of how this might look. **DO NOT LOOK AT THE SOURCE CODE! THAT'S CHEATING!!**
