# MMM-Meniny
Slovak name of day (request of Maros)

## Installation
```shell
cd ~/MagicMirror/modules
git clone https://github.com/eouia/MMM-Meniny
```

## Configuration
```javascript
{
  module: "MMM-Meniny",
	position: "top_left",
	config: {
	  message: "Today is <i>$TODAY$</i>. <br/> Tomorrow is <i>$TOMORROW$</i>."
    // you can use $TODAY$ as name of today, $TOMORROW$ as name of tomorrow.
	}
},
```

I haven't fully test.
