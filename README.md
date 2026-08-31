# cordova-plugin-geolocation-raw

Cordova Android Geolocation (raw)

# Install

```bash
cordova plugin add https://github.com/mattiabottes/cordova-plugin-geolocation-raw
```

## getLocation

### Success return data

- latitude
- longitude
- isMock

# Usage

```Javascript
	RawLocation.getLocation({ }, function (locationInfo) {
		console.log(JSON.stringify(locationInfo));
	}, function (err) {
		console.log(err);
	});
```
