<center><h1>vMCShop Standard ;)</h1></center>
<br><br>
<h2>Wymagania</h2>
<ul>
    <li>PHP 5.6</li>
    <li>MySQL</li>
    <li>Aktywne mod_rewrite</li>
</ul>
<br>
<h2>Poradnik jak poprawnie wgrać sklep</h2>
<ol>
  <li>Wgraj pliki na serwer <b>www</b></li>
  <li>Importuj plik <b>sklep.sql</b> do swojej bazy danych MySQL.</li>
  <li>Edytuj plik <b>application/config/config.php</b>. Zmienną <b>$config['base_url']</b> ustaw na adres do swojej witryny. Przykład $config['base_url'] = 'https://vmcshop.pro/'.</li>
  <li>Edytuj plik <b>application/config/database.php</b>. Zmienne <b>'hostname' => 'adres bazy danych', 'username' => 'nazwa użytkownika bazy danych', 'password' => 'hasło do bazy danych', 'database' => 'nazwa bazy danych'</b> ustaw na wartosci odpowiadające Twojej bazie danych.</li>
  <li>Przejdź do witryny <b>twojadomena.com/admin</b> i zaloguj się używając domyslnych danych. (<b>Login: Admin, Hasło: password</b>).</li>
  <li>Sklep jest gotowy do użycia.</li>
<ol>
