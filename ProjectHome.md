Entering data into minute keypads on mobile devices is a slow and tedious process.  The user has to move thumb or stylus from one tiny key to another.  In a speed competition in 2005, a retired 93-year-old telegraph operator sent a text message verbatim via Morse code quicker that a teenager was able to send the same message via a mobile phone using predictive text and common abbreviations (<a href='http://www.engadget.com/2005/05/06/morse-code-trumps-sms-in-head-to-head-speed-texting-combat/'>see here</a>), which illustrates just how awkward it is to enter text into mobiles.

This project shows that text can be entered into a device using just a five key keyboard.  It includes an HTML page with embedded JavaScript that demonstrates the approach.  On a real mobile device, the five keys could be operated by the fingers and thumb of one hand without having to move them from one key to another, which is what slows text entry on mobiles today.

Chording keyboards have been around for quite a long time (see <a href='http://en.wikipedia.org/wiki/Chording_keyboard'>this Wikipedia article</a>), but traditional five-key devices offer only 2^5-1 = 31 code combinations (or 57 combinations if abbreviated sequences are accepted), which is not enough.  This demo uses sequence-dependent coding, which together with abbreviated sequences offers 324 different code combinations -- well in excess of what a full-size PC keyboard offers.

An on-line demo of the sequenced chording keyboard is available <a href='http://turton.co.za/chordingKeyboard/chordingKeyboard.html'>here</a>, and <a href='http://trevors-trinkets.blogspot.com/2007/07/five-finger-keyboards.html'>my blog entry</a> discusses the ideas behind this project.