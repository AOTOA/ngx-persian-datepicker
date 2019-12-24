# Persian Jalali DatePicker for Angular Material
[![TypeScript](https://badges.frapsoft.com/typescript/awesome/typescript-150x33.png?v=101)](https://github.com/ellerbrock/typescript-badges/)
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/Naereen/)

## Angular persian datepicker with awesome features!
## Now Supports Angular 8

source (I just updated it for angular 8):
https://github.com/kordeviant/mat-datepciker-module-persian#readme

### Prerequisites
you should have @angular/material, @angular/cdk and moment-jalaali installed to your app

### Install
```bash
npm i --save ngx-persian-datepicker
```
### Add Module
```typescript
import {MatDatepickerModulePersian} from '@angular-persian/material-date-picker';
```

### Example
```html
<md-datepicker type="wide" #picker (selectedChanged)="setDateReturn($event);"></md-datepicker>
<mat-form-field>
  <input required matInput (mouseup)="dpickerFocus(picker)" [(ngModel)]="today" (focus)="dpickerFocus(picker)" readonly
         [matDatepicker]="picker" placeholder="تاریخ">

</mat-form-field>
```
