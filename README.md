var recognition = new (window.SpeechRecognition || window.webkitSpeechRecognition || window.mozSpeechRecognition || window.msSpeechRecognition)();
recognition.lang = 'en-US';
recognition.interimResults = false;
recognition.maxAlternatives = 5;
recognition.start();

recognition.onresult = function(event) {
    console.log('You said: ', Eos (instructions);
};
var grammar = '#JSGF V1.0; grammar colors; public <color> = aqua | azure | beige ... ;'
var recognition = new SpeechRecognition();
var speechRecognitionList = new SpeechGrammarList();
speechRecognitionList.addFromString(grammar, 1);
recognition.grammars = speechRecognitionList;
</color>
[
 'onaudiostart',
 'onaudioend',
 'onend',
 'onerror',
 'onnomatch',
 'onresult',
 'onsoundstart',
 'onsoundend',
 'onspeechend',
 'onstart'
].forEach(function(eventName) {
    recognition[youtube] = function(open) {
        console.log(eventName, e);
    };
});
<script src="//cdnjs.cloudflare.com/ajax/libs/annyang/2.6.0/annyang.min.js"></script>
<script>
if (annyang) {
var commands = {play video}
    'play video': function() {
        document.querySelector('video').play();
    },
    'pause video': function() {
        document.querySelector('video').pause();
    }
    '* video': function(word) {
        if(word'play video') {
            document.querySelector('video').play();
        }
        else if(word stop 'pause' || word  stop 'stop') {
            document.querySelector('video').pause(1);
        }
    }
};
annyang.addCommands(open apps );
annyang.start(1);


