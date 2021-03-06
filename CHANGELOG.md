# node-red-contrib-boolean-logic-ultimate
[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg?style=flat-square)](https://www.paypal.me/techtoday) 

<a href="http://eepurl.com/gJm095" target="_blank">Subscribe to my channel.</a> Only news about my nodes, no spam, no ads. I'm a github developer, not a merchant.

<p>
<b>Version 1.0.20</b> August 2020<br/>
- NEW: Inject Node. The pourpose of this node is to speed up the testing of you flow, by issuing true/false command by pushbutton on the node itself. This node is simpler as the default node-red inject node.</br>
</p>
<p>
<b>Version 1.0.19</b> August 2020<br/>
- NEW: Simple Output node. The pourpose of this node is to send a message with payload TRUE on the first pin and FALSE on second pin, independently from the msg input.</br>
</p>
<p>
<b>Version 1.0.18</b> August 2020<br/>
- Boolean Logic: warn user if either topic or payload are not set. You must always set a topic and payload.</br>
</p>
<p>
<b>Version 1.0.17</b> June 2020<br/>
- Interruptflowultimete: State save/replay. Msg.play = true sends the current payload See the README on github for an example.</br>
</p>
<p>
<b>Version 1.0.16</b> May 2020<br/>
- BlinkerUltimate: if you set the interval while the blinker is running, yet the new interval is applied immediately.</br>
</p>
<p>
<b>Version 1.0.15</b> May 2020<br/>
- Adjusted status of Boolean Logic ultimate. Replaced the text "null", with --- for better understanding.</br>
</p>
<p>
<b>Version 1.0.14</b><br/>
- NEW: added blinker node. Thanks to @Marco for the suggestion.</br>
</p>
<p>
<b>Version 1.0.12</b><br/>
- Boolean Logic, FilterUltimate and InvertUltimate now output the entire message input, replacing only topic and payload.</br>
</p>
<p>
<p>
<b>Version 1.0.11</b><br/>
- Enhanced help.</br>
</p>
<p>
<b>Version 1.0.10</b><br/>
- Fix a possible issue in the "Interrupt Flow", if the trigger topic contains special characters.</br>
</p>
<p>
<b>Version 1.0.9</b><br/>
- Added "Interrupt Flow" node. Whenever the node receives a payload = false from a specific topic, it stops output messages to the flow. As soon it receives payload = true from this topic, the output messages start to flow out again.</br>
</p>
<p>
<b>Version 1.0.8</b><br/>
- Updated Help
</p>
<p>
<b>Version 1.0.7</b><br/>
- Node node shows "f" when "filter true" is selected and "t" (triggername) when "trigger only by single topic" is selected.<br/>
</p>
<p>
<b>Version 1.0.6</b><br/>
- Stripped out the date/time in node status<br/>
</p>
<p>
<b>Version 1.0.5</b><br/>
- Added the Last value change date/time in the status.<br/>
- Correction in the in-line help<br/>
- Better format of the README.md<br/>
</p>
<p>
<b>Version 1.0.4</b><br/>
- Added the option to initialize the undefined inputs with true or false. Thanks to this, the node is immediately operative (will not wait until all topis arrives).<br/>
</p>
<p>
<b>Version 1.0.3</b><br/>
- Node status: cosmetic adjustments<br/>
</p>
<p>
<b>Version 1.0.2</b><br/>
- Added "trigger mode" option (fixed UI glitch)<br/>
</p>
<p>
<b>Version 1.0.1</b><br/>
- Added "trigger mode" option<br/>
</p>
<p>
<b>Version 1.0.0</b><br/>
- Added Filter node<br/>
</p>
<p>
<b>Version 0.0.8</b><br/>
- Delete persistent states when a new unexpected topic arrrives<br/>
- Better status representation<br/>
- Better and clearer configuration UI <br/>
</p>
<p>
<b>Version 0.0.7</b><br/>
- Fixed decimal error in the "Invert" node.<br/>
</p>
<p>
<b>Version 0.0.6</b><br/>
- Fixed crappy "Invert" node.<br/>
</p>
<p>
<b>Version 0.0.5</b><br/>
- Bypass persistency if node-red user hasn't permissions to write to the filesystem.<br/>
</p>
<p>
<b>Version 0.0.4</b><br/>
- Fixed conflict issue if you have the old boolean logic installed<br/>
</p>
<p>
<b>Version 0.0.3</b><br/>
- Fixed status display<br/>
</p>
<p>
<b>Version 0.0.2</b><br/>
- Fixed persistent state deletion upon node update/delete<br/>
</p>
<p>
<b>Version 0.0.1</b><br/>
- Initial release<br/>
</p>