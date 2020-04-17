# anabel
A beautiful personal website template, built on TailwindCSS.

![Image of Anabel page](https://github.com/klickers/anabel/blob/master/dist/anabel.PNG)

## Usage
### CDN
Insert `before.css`, the main CSS file, into your page's `<head>`:
```
<link href = "https://cdn.jsdelivr.net/gh/klickers/anabel@latest/dist/before.css" rel = "stylesheet" />
```

### Download
Download and extract the contents of this repository.  Inside the root directory, run:
````
> npm install
> npm start
````
*Note:  A production build is also available at `dist/`.*

That's it!  You're all set to go.


## More Information

To customize the styling, edit `src/before.css` and then compile:
````
> parcel build src/index.html
````
The `/dist/` folder will contain the compiled files you need.  (Running `npm start` will give you similar results.)
