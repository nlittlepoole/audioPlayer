# audioPlayer

Audio file player and visualizer based on the Web Audio API

Demo: [Click Here](http://root.gakup.com/audio_player)

## Browser Support: 
- Chrome (webkit) v14
- Firefox (gecko) v23
- Opera (webkit) v15
- Safari (webkit) v6

## Quick Guide:
```javascript
$(window).load(function () {
	$("#audioWrapper").audioPlayer({
		playlist: [
			{src: "filename1.mp3"},
			{src: "filename2.mp3"},
			{src: "filename3.mp3"}
		]
	});
	
	$("#audioWrapper").audioPlayer().play();
});
```