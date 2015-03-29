# MTimePicker
<h4>Simple HTML TimePicker for Mobile Devices</h4>
"M" may stands for Maikon, Mobile, Minimal or My Time Picker

Does not require jQuery.

<h4>Usage:</h4>
<h5>Include the MTimePicker.js</h5>
<code>
&lt;script src="js/MTimePicker.js"&gt;&lt;/script&gt;
</code>
<h5>Apply the input you want to use time picker, passing the id or the element and a Title as arguments:</h5>
<pre>
  MTimePicker.Apply('inputAlarm', 'Select a time:');
</pre>
<h5>You can also choose the classes the input and buttons have:</h5>
<pre>
  MTimePicker.Config.InputClass = "form-control";
  MTimePicker.Config.ButtonClass = "form-control btn btn-soul";
  MTimePicker.Apply('txtHoraInicial', 'Escolha a Hora Inicial:');
  MTimePicker.Apply('txtHoraFinal', 'Escolha a Hora Final:');
</pre>
<h4>Screenshot:</h4>
<a href="http://maikonfarias.com/blog/wp-content/uploads/2015/03/MTimePicker_screenshot.png"><img class="alignnone size-full wp-image-357" src="http://maikonfarias.com/blog/wp-content/uploads/2015/03/MTimePicker_screenshot.png" alt="MTimePicker_screenshot" width="280" height="533" /></a>
