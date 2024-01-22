## React Project Setup along with Tailwind CSS
### Follow these Steps => 
```bash
1. Go to Tailwind.css Website 
2. Click on Docs
3. Select Framework Guides
4. Select Vite
5. Follow the Commands 
```
## Create React App using Vite
### Dowloads NodeJs from official Website
```css
$ npm create vite@latest
$ Project Name : "My Project"
$ Select Framework : React
$ Select Variant : Javascript
```
### Final Commands
```css
$ cd "My Project"
$ npm install [To get Node Modules]
$ npm run dev
```

### Now, We will Integrate Tailwind CSS in React
<div style= "color:black; font-weight:800; background-color:white; text-align:center">1.Install Tailwind Css</div>

```
$ npm install -D tailwindcss postcss autoprefixer
$ npx tailwindcss init -p
```
<div style= "color:black; font-weight:800; background-color:cyan; text-align:center">2.Configure Your Template Paths in <span style="font-style:italic; color:blue">"tailwind.config.js"</span> file</div>

```css
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
```
<div style= "color:black; font-weight:800; background-color:yellow; text-align:center">3. Add the Tailwind directives to your CSS in <span style="font-style:italic; color:red">"index.css"</span> file</div>

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
<div style= "color:black; font-weight:800; background-color:white; text-align:center">4.Start Your Build Process <span>in "Terminal"</span></div>

```bash
$ npm run dev
```
<div style= "color:black; font-weight:800; background-color:pink; text-align:center">5.Start Building Project Using React with Tailwind</div>

```js
export default function App() {
  return (
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>
  )
}
```
#### Thank You To Visit Our Setup Guide 🚀