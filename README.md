
# NgFyCircleChart

Hi, its my first angular package. If find any bug or have any questions please ask me. Enjoy.


## Installation

  

    npm i ng-fy-circle-chart

  
  
## Import

  ```ts
  import { NgFyCircleChartComponent} from  'ng-fy-circle-chart';
   ```
  
```ts
@NgModule({
	declarations: [
		AppComponent,
		NgFyCircleChartComponent // add this
	],
	imports: [
		BrowserModule,
	],
	providers: [],
	bootstrap: [AppComponent]
})
```


## Usage
  
```html
<fy-circle-chart></fy-circle-chart>
```

add this code to html file



## Attributes

	
| Name | Type | Default | Description |
|--|--|--|--|
| percent | number | 60 | Circle value. Max 100, Min 0 |
|size|number|150|Canvas height and width
|backgroundColor|string|#ccc|Circle background color not canvas. Hex or rgb color.
|color|string or fyColor[]|#ff0000|Circle active color. Hex or rgb. fyColor for smooth color change by percent. fyColor detail is under this table.
|textColor|string|#4b4b4b|Percent and custom text color. Hex or rgb color.
|lineWidth|number|10|Cirle width
|hoverLineWidth|number|lineWidth|Circle width on hover. Try it, its smooth.
|startDelay|number|0|Delay to start animation. For smooth page loading.
|text|string[]|[]|Custom text. Not Recommended more then 2.
|percentFontSize|string|30px|Percent font size
|textFontSize|string|16px|Custom Text font size
|horizontalAlign|string|center|If parent element width bigger then size its justify
|animation|boolean|true|Recommended set false when use multi at same page 
|skeleton|boolean|false|Skeleton loading option
|fps|number|20|Count of update for second.
|tickAngle|number|10|Every update, add or minus count. Not percent its angle. Max 360 (Not Recomended), Min 1.

### fyColor
```json
	{
		percent:number,
		r:number,
		g:number,
		b:number
	}
```
its an interface if u want  import to component or use it as u want.

Remember color is string or fyColor[]

	

## Quick Contact

Mail to tahsincesur1@gmail.com

## Keywords
angular, angular2, ng, ngx, ng2, angular6, angular7, circle, chart, circle chart, Angular circle chart, ng circle chart
