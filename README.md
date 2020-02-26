# CookieJS
Cookie Library in Javascript

## Usage

#### Initalize
```javascript
var cookie = new Cookie();
```

#### Create Cookie

```javascript
cookie.set("username","Freedom");
```

#### Get Cookie

```javascript
// Cookie Key 
cookie.username.key

// Cookie Value
cookie.username.value

```

#### Remove Cookie

```javascript
cookie.remove();
```

#### Search Cookie

```javascript
// String Search
cookie.get("username");

// Regex Search
cookie.get(/name$/);
```
