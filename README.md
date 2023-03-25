<div align="center">
<h1><p></p>Register System<p></p></h1>
<img src="https://github.com/AmxxPro-pl/.github/blob/main/Banner-new.png"></img>
</div>

---

### Description
- Rozbudowany system Rejestracji Nicku
- Możliwość zbanowania przez admina konta, zmiany hasła, odbanowania konta z poziomu serwera
- Zakaz usunięcia konta gdy rejestracja jest obowiązkowa, możliwość zmiany hasła przez gracza
- Po X nieudanych próbach wpisania hasła, gracz zostaje zbanowany na 30 min, a gdy upłynie czas na zalogowanie się/zarejestrowanie się otrzymuje on kicka
- Takowy plugin trudno będzie ocenić po zdjęciach, także zapraszam do kontaktu by przetestować go osobiście :D
- Dwie wersje pluginu - zapis pod nVault oraz do pliku ini.

### Configure
<details>
  <summary><b>registersystem_pro.cfg</b></summary>

```
//===================== » Register System - Configuration « =====================
//                     Aut(h)or pluginu: N1K1Cz
//                     Strona: © AmxxPro.pl

//Glowny prefix pluginu ( AmxxPro.pl - Domyślnie )
amxxpro_register_prefix "AmxxPro.pl"

//Czy rejestracja ma byc obowiazkowa? ( 1 - Domyślnie )
amxxpro_register_necessary "1"

//Ile sekund ma gracz na zarejestrowanie/zalogowanie sie? ( 60 - Domyślnie )
amxxpro_register_logintime "60"

//Ile gracz ma miec prob na wpisanie hasla? ( 3 - Domyślnie )
amxxpro_register_attempts "3"

//Ile znakow minimalnie musi posiadac haslo? ( 6 - Domyślnie )
amxxpro_register_passwordlen "6"

//Nazwa forum potrzebnego do odwolania sie w przypadku zapomnienia hasla ( AmxxPro.pl - Domyślnie )
amxxpro_register_forum "AmxxPro.pl"

//Flaga admina potrzebna do zbanowania/odbanowania/zmiana hasla graczowi ( a - Domyślnie )
amxxpro_register_adminflag "a"

//===================== » Register System - Configuration « =====================

```
</details>
<details>
  <summary><b>registerban_pro.cfg</b></summary>

```
; Przykład:(plik tworzy sie automatycznie)

"N1K1Cz" "Powód Bana: Zbyt szybkie nabijanie EXP - mozliwe cheaty"
```
</details>
<details>
  <summary><b>registerplayers_pro.ini</b></summary>

```
; Przykład: (plik tworzy sie automatycznie)

"N1K1Cz" "haslo1234" "1"
```
</details>

### ScreenShots

<details>
  <summary><b>Server</b></summary>
  
  - Login Menu (Full)
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/Login_Menu.png"></img>

  - Register Menu (Full)
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/Register_Menu.png"></img>
  
  - Admin Menu (po kliknięciu w pierwszą opcję zmieniamy co chcemy zrobić)
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/Admin_Menu.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/Menu_Ban.png"></img>
  
  - Ban Console
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/Ban_Console.png"></img>
  - Password Information
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/Bad_Password.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/Change_Password.png"></img>
  
  - Delete Account
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/delete_account.png"></img>
  
  - Information MOTD
  
  <img src="https://github.com/AmxxPro-pl/Register-System/blob/main/img/Information.png"></img>
</details>

### Requirements 
- AMXModX 1.9 / AMXModX 1.10
