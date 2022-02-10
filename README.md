# jquery-textarea-library
TextArea is a jQuery plugin that automatically count and limit number of characters , no of lines along with progressbar

##Requirements

jQuery
##Installation

Copy the TextArea file to your resources directory and then simply link to the file in your HTML document.

<script src="jquery.textArea.js" type="text/javascript"></script>


##Using TextArea

To run TextArea, simply run the function on any textarea elements matched with jQuery, like so:

$('textarea').textareaCounter({
    txtElem:'textarea',
    charElem:'charCount',
    lineElem:'lineCount',
    progElem:'progress-percent',
	progPerc:'progPercentage',
    txtCount:'100',
    lineCount:'10',
    charPerLine:'10'
});

Refer example file index.html for more details on html elements required.


##Released under the BSD License

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.