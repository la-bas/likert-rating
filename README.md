#Likert Rating jQuery Plugin

jQuery plugin which creates a likert scale rating bar from a form select element.

## Usage

Include jquery.color.min, likert-rating.js and likert-rating.css.

Make a html form with one or more select element:

	<form>
		<select class="my-likert-scale">
    			<option val="something-1">Strongly disagree</option>
    			<option val="something-2">Disagree</option>
    			<option val="something-3">Neutral</option>
    			<option val="something-4">Agree</option>
    			<option val="something-5">Strogly agree</option>
  		</select>
	</form>

Then call the jQuery plugin:

	$('.my-likert-scale').likert()

## Configuration

animationTime: 500

colors: ["ff0000", "ff9900", "ffff00", "ccff00", "33cc00"],

backgroundColor: "#333",

infoBox: true,

selectCallback: function() {}
