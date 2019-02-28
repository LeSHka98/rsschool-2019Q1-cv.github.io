#RESUME   
##1. Name
Alexei Petrovskiy
##2. Contacts
  E-mail: pas1-by@yandex.ru
  mobile: +375447381891
##3. Summary
  I want  to become a highly qualified specialist, become worthy and  
  respected member of society.I want to have worthy salary to provide
  with money myself and my family.I'll make every effort to succeed.
  Web - the specialization that in my mind suita me more than others 
  and i like it more than others.
## 4. Skills
C++ and JavaScript basics, HTML and CSS(flexbox , grid)
##5. Code example
    $(document).ready(function () {

      // VARIABLES
      var calc = $('.calculator');
      var calcDisplay = calc.find('.calculator__display');
      var calcKeys = calc.find('.calculator__key');
      var calcButton = calc.find('.calculator__button');
      var calcClear = calc.find('.calculator__clear');
      var calcEqual = calc.find('.calculator__key--equal');
      var calcPower = calc.find('.calculator__power');
      var calcSpace = calc.find('.calculator__backspace');

      // INIT CALC KEYS
      calcKeys.each(function () {
          var current = $(this).attr('value');
          $(this).text(current);
      });

      // ADD NUMBERS TO INPUT
      calcButton.on('click', function () {
          calcDisplay.val( calcDisplay.val() + $(this).attr('value') );
      });

      // CLEAR INPUT
      calcClear.on('click', function () {
          calcDisplay.val('');
      });

      // SHOW RESULT
      calcEqual.on('click', function () {
          calcDisplay.val( eval( calcDisplay.val() ) );
      });

      // POWER BUTTON
      calcPower.on('click', function () {
          calcDisplay.val( Math.pow( calcDisplay.val(), 3 ) );
      });

      // BACKSPACE BUTTON
      calcSpace.on('click', function () { // http://www.w3schools.com/jsref/jsref_substring.asp
          calcDisplay.val( calcDisplay.val().substring(0, calcDisplay.val().length-1) );
      });

     });

##6. Expirience
1. Website development varying complexity(companies sites, business cards)
2. development of information control systems
3. SEO optimization

##7. Education
Now I'm studying at BSUIR on the 3d course(speciality of ASOI)

##8.  English
Pre-intermediate level. I've attended english courses from 7 to 10 grade.