# Laravel Blade Custom Directive
Laravel Blade: Custom Directive (Component)

#### Currency Rrupiah
```ruby
Blade::directive('currency', function ( $expression ) { return "Rp. <?php echo number_format($expression,0,',','.'); ?>"; });
```
### Output
> @currency($data->values)
> <br>
> Rp. 786.000.000
