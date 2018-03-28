# ion-datetime-picker
ionic时间插件
============
### 基于ionic3
<div class="list">
<div class="item item-divider">Date picker</div>
<div class="item item-icon-left" ion-datetime-picker date ng-model="dateValue">
<i class="icon ion-ios-calendar positive"></i> Click me to open the date picker:
<strong>{{dateValue| date: "yyyy-MM-dd"}}</strong>
</div>
<div class="item item-icon-left" ion-datetime-picker date monday-first ng-model="dateValue">
<i class="icon ion-ios-calendar-outline positive"></i> Monday as the first day of the week:
<strong>{{dateValue| date: "yyyy-MM-dd"}}</strong>
</div>
<div class="item item-divider">Time picker</div>
<div class="item item-icon-left" ion-datetime-picker time ng-model="timeValue">
<i class="icon ion-ios-clock positive"></i> Basic time picker:
<strong>{{timeValue| date: "H:mm"}}</strong>
</div>
<div class="item item-icon-left" ion-datetime-picker time seconds ng-model="timeValue">
<i class="icon ion-ios-time positive"></i> With seconds:
<strong>{{timeValue| date: "H:mm:ss"}}</strong>
</div>
<div class="item item-icon-left" ion-datetime-picker time am-pm ng-model="timeValue">
<i class="icon ion-ios-clock-outline positive"></i> 12-hour clock:
<strong>{{timeValue| date: "h:mm a"}}</strong>
</div>
<div class="item item-icon-left" ion-datetime-picker time am-pm seconds ng-model="timeValue">
<i class="icon ion-ios-time-outline positive"></i> Combined:
<strong>{{timeValue| date: "h:mm:ss a"}}</strong>
</div>
<div class="item item-divider">Datetime picker</div>
<div class="item item-icon-left" ion-datetime-picker ng-model="datetimeValue">
<i class="icon ion-ios-grid-view-outline positive"></i> Basic datetime picker:
<strong>{{datetimeValue| date: "yyyy-MM-dd H:mm"}}</strong>
</div>
<div class="item item-icon-left" ion-datetime-picker seconds am-pm ng-model="datetimeValue">
<i class="icon ion-ios-barcode-outline positive"></i> With seconds and 12-hour clock:
<strong>{{datetimeValue| date: "yyyy-MM-dd h:mm:ss a"}}</strong>
</div>
<div class="item item-icon-left" ion-datetime-picker monday-first ng-model="datetimeValue">
<i class="icon ion-ios-browsers-outline positive"></i> Monday as the first day:
<strong>{{datetimeValue| date: "yyyy-MM-dd H:mm"}}</strong>
</div>
<div class="item item-icon-left" ion-datetime-picker monday-first seconds am-pm ng-model="datetimeValue">
<i class="icon ion-ios-lightbulb-outline positive"></i> Everything together:
<strong>{{datetimeValue| date: "yyyy-MM-dd h:mm:ss a"}}</strong>
</div>
</div>



