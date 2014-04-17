## Client Side Templates
```html
<li class='list-group-item class-listing' ng-repeat='class in classes'>
    <div class="row class-row">
        <div class="col-md-3">{{class.classNum}}</div>
        <div class="col-md-5">{{class.title}}</div>
        <div class="col-md-2">{{class.dayTimes}}</div>
        <div class="col-md-2">{{class.instructor}}</div>
    </div>
</li>
```
![client side template](images/cs-template.png)
