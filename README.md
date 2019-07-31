# laravel-websocket-fix
**sory bad english**<br>
-this file is for version laravel 5.8 ++ which getting error when run <br>
<code> php artisan websocket:serve </code><br>
and getting error message 
*Class BeyondCode\LaravelWebSockets\Statistics\DnsResolver may not inherit from final class (React\Dns\Resolver\Resolver)*<br>
**TO FIX THAT**<br>
-after you install a ***laravel-websocket*** from beyondcode <br>
-copy all of this file to 
copy all file inside laravel-websocket-fix to<br>
<code>{{ root.of.laravelFolder }}/vendor/beyondcode/laravel-websocket</code> replace all file with new file and then
<br>
-run <code> php artisan websocket:serve </code><br>

<br>
*this file not so different with original file, it's just change some function and class and resolve namespace use*
