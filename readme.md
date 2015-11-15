# Readme
React.js component which helps to embed fluid inline cross-browser svg artworks to the page.

## Install
```
npm install --save react-fluid-svg
```

## Usage
```
import FluidSvg from "react-fluid-svg";
export default class MyComponent extends Component {
   render() {
      return (
         <FluidSvg width="20">
            <svg version="1.1" viewBox="0 0 20 20">
               <path d="M2.643,6.357c1.747-1.5,3.127-2.686,6.872-0.57c1.799,1.016,3.25,1.4,4.457,1.398c2.115,0,3.486-1.176,4.671-2.193
                  c0.423-0.363,0.477-1.008,0.122-1.439c-0.357-0.432-0.987-0.488-1.41-0.125c-1.746,1.502-3.127,2.688-6.872,0.57
                  C5.535,1.205,3.217,3.195,1.355,4.795C0.933,5.158,0.879,5.801,1.234,6.234C1.59,6.664,2.22,6.721,2.643,6.357z M17.355,8.535
                  c-1.746,1.5-3.127,2.688-6.872,0.57C5.535,6.31,3.217,8.301,1.355,9.9c-0.422,0.363-0.477,1.008-0.121,1.439
                  c0.355,0.432,0.986,0.488,1.409,0.125C4.39,9.963,5.77,8.777,9.515,10.892c1.799,1.018,3.25,1.4,4.457,1.4
                  c2.115,0,3.486-1.176,4.671-2.195c0.423-0.363,0.477-1.008,0.122-1.438C18.409,8.226,17.778,8.172,17.355,8.535z M17.355,13.641
                  c-1.746,1.502-3.127,2.688-6.872,0.572c-4.948-2.795-7.266-0.805-9.128,0.795c-0.422,0.363-0.477,1.008-0.121,1.439
                  c0.355,0.432,0.986,0.486,1.409,0.123C4.39,15.07,5.77,13.885,9.515,16c1.799,1.016,3.25,1.4,4.457,1.4
                  c2.115,0,3.486-1.178,4.671-2.195c0.423-0.363,0.477-1.008,0.122-1.439C18.409,13.334,17.778,13.279,17.355,13.641z"/>
            </svg>
         </FluidSvg>
      );
   }
}
```

Pay attention to child svg `viewBox` prop, it's required.


## Props
`center`: center the container, defaults to: `false`
`width`: container width, `number`, `required`
`height`: container height, defaults to: `width`
`minWidth`: Minimum container width, defaults to: `0`
`maxWidth`: Maximum container width, defaults to: `width`
