<h1>Task Manager created using Laravel-Vue </h1>

# Getting Started :dart:
<ul>
    <li>User can can create/register his/her account</li>
    <li>User can log out and log on registered account</li>
    <li>Registered Users can assign task to other registered user</li>
    <li>Registered Users can create,  edit, update, and delete task </li>
    <li>CRUD resources on Task</li>
<li>Email notification to users after task creation and completion</li>
 </ul>
 
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="git clone https://github.com/Veejay15/veejay-s-todo.git
Run command composer install
Run cp .env.example .env
">
<pre><code>Clone project repository:  git clone https://github.com/Veejay15/veejay-s-todo.git
Run command composer install
Make a copy of the .env.example file to .env. You can do that by running cp .env.example .env
</code></pre>
</div>
<p>Then create the necessary database.</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="php artisan db
create database blog
">
<pre>
<code>php artisan db
create database taskmanagement
Generate app key by running php artisan key:generate
</code>
</pre>
</div>
<p>And run the initial migrations and seeders.</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="php artisan migrate --seed
">
<pre><code>php artisan migrate --seed
</code></pre>
</div>
