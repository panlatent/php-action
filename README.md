# PHP Action

PHP Action declares some common interfaces that defines an action for use by all PHP programs.


```php
interface ActionInterface
{
    public function run(): void;
}
```

Any code, library, and framework can implement an action based on this interface and then call it anywhere. 
An action can be any operation, such as sending an HTTP request, a controller response, or sending an email.
