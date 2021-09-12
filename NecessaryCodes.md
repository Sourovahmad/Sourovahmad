# Get Route Key Name


 On Route Model Binding its default searching with id. so if you want to Bind with any other parameter from database you just create a funtion on model like at the top




```
public function getRouteKeyName(){
	return 'id'
}

```




Another Way is Specify in Route


```
Route::get('products/{product::category}', 'yourcontroller::class');

```