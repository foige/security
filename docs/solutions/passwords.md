---
title: პაროლების მენეჯერი
icon: material/key-variant
---

# პაროლების მენეჯერი


პაროლები აუთენტიფიკაციის ყველაზე გავრცელებული ფორმაა, თუმცა ადამიანისთვის
შეუძლებელია განსხვავებულ სისტემებისთვის განსხვავებული, ძლიერი პაროლის მოფიქრება და დამახსოვრება,
რაც საფრთხეში აგდებს უსაფრთხოებას.

/// admonition |
    type: failure
სხვადასხვა სისტემაზე ერთი და იგივე პაროლის გამოყენება ნიშნავს, რომ თუნდაც ერთ სისტემაში
დაუცველობის აღმოჩენის, ან ამ სისტემის უკან მდგომი პირების არაკეთილსინდისიერების შემთხვევაში,
ბოროტმოქმედები წვდომას მოიპოვებენ ყველაფერზე, სადაც ეს პაროლი იყო გამოყენებული

პაროლის სიმძლავრის მთავარი განმსაზღვრელი ენტროპიაა, ანუ რამდენად არაპროგნოზირებადია ის.
ადამიანისთვის შეუძლებელია ასეთი პაროლების მოფიქრება და შემდეგ, მათი დამახსოვრება.
///


## პაროლების მენეჯერი

/// admonition |
    type: success

პაროლების მენეჯერები გვაძლევენ საშუალებას, რომ ყველა საიტსა, სისტემასა თუ აპლიკაციაში, განსხვავებული
პაროლი გვქონდეს. ის ავტომატურად დააგენერირებს რთულ პაროლს და ავტომატურად შეავსებს ყველგან,
სადაც ეს შესაძლებელია, ხოლო იქ, სადაც ავტომატური შევსება ვერ მოხდება, ყოველთვის შეგეძლებათ
პაროლის დაკოპირება და ხელით ჩასმა.

პაროლების მენეჯერების მონაცემთა ბაზა დაშიფრულია, რაც ნიშნავს იმას,
რომ მასში შენახულ პაროლებზე წვდომა ექნება მხოლოდ მას, ვისაც აქვს გასაღები.
///

აუცილებელია ისეთი პაროლების მენეჯერის გამოყენება, რომლის კოდიც საჯაროდ ხელმისაწვდომია. საჯაროობა
უზრუნველყოფს საუკეთესო უსაფრთხოებას და სანდოობა არა სიტყვებით, არამედ ქმედებებით მიიღწევა.

## რეკომენდირებული პაროლების მენეჯერი

<div class="grid cards" markdown>

- ![Bitwarden](../assets/img/logo/bitwarden.svg){ .lg .middle .twemoji } [Bitwarden](https://bitwarden.com/){:target="_blank"}

    **მათთვის, ვისაც სიმარტივე ურჩევნია**

    ---
    **Bitwarden** არის ღია წყაროს მქონე და უფასო პაროლების მენეჯერი.

    ის ავტომატურად ქმნის ძლიერ, უსაფრთხო პაროლებს და უზრუნველყოფს მათ სინქრონიზაციას ყველა 
    მოწყობილობაზე. **Bitwarden** იყენებს მაღალი დონის შიფრირებას მონაცემების დასაცავად.

    მომხმარებლებისთვის ხელმისაწვდომია ბრაუზერის გაფართოებები და მობილური აპლიკაციები როგორც iOS, ისე Android პლატფორმებისთვის.

</div>

<div class="grid cards" markdown>

- ![KeePassXC](../assets/img/logo/keepassxc.svg){ .lg .middle .twemoji } [KeepassXC](https://keepassxc.org/){:target="_blank"}

    **მათთვის, ვინც მარტივად აგვარებს ტექნიკურ პრობლემებს**

    ---
    **KeepassXC** არის ღია წყაროს მქონე და უფასო პაროლების მენეჯერი, რომელიც **KeePass** სტანდარტის
    დაშიფრულ მონაცემთა ბაზას იყენებს.

    **Bitwarden**-ისგან განსხვავებით, აპლიკაცია სრულად ინტერნეტის გარეშე მუშაობს, ის ჩვეულებრივ
    დაშიფრულ ფაილს ქმნის მოწყობილობაზე, რომელშიც თქვენი პაროლები ინახება.

    **KeepassXC** ძალიან უსაფრთხოა. მისი აპლიკაციები სხვადასხვა ოპერაციულ სისტემებზე
    სწორ პარამეტრებს იყენებენ 
   (როგორიცაა მაგალითად [macOS/iOS kSecAttrAccessible](https://developer.apple.com/documentation/security/ksecattraccessible){:target="_blank"}, ან [StrongBox](https://source.android.com/docs/security/best-practices/hardware){:target="_blank"} ანდროიდზე).

    მობილურისთვის, Android-ზე რეკომენდებულია [KeepassDX](https://www.keepassdx.com/){:target="_blank"} აპლიკაცია, ხოლო iOS-ზე - [KeePassium](https://keepassium.com/){:target="_blank"}.

    სინქრონიზაციისთვის, შეგიძლიათ KeepassXC-ის მიერ შექმნილი ბაზის ფაილი შეინახოთ ფოლდერში,
    რომელიც ავტომატურად სინქრონიზდება მოწყობილობებს შორის (მაგ. Dropbox, Google Drive, iCloud, Syncthing და ა.შ.).

</div>

**Bitwarden** გამოირჩევა ძალიან მაღალი უსაფრთხოებით და მარტივი გამოყენებით, ხოლო **KeePassXC** მაქსიმალური
უსაფრთხოებით და მომხმარებლისგან უფრო მაღალი ტექნიკური ცოდნის მოთხოვნით. 
ამიტომ, ზოგადი რეკომენდაციაა **Bitwarden**-ის გამოყენება და საიტზე ინსტრუქციების მაგალითებშიც
**Bitwarden**-ს გამოვიყენებთ.

ორივე პაროლების მენეჯერი მაღალი უსაფრთხოების მქონეა და არჩევანში ვერ შეცდებით, **KeePassXC**-ს უბრალოდ 
უფრო მეტი უსაფრთხოების სისტემა აქვს ინტეგრირებული და საწყის ეტაპზე, მომხმარებლისგან მეტ ტექნიკურ უნარ-ჩვევებს მოითხოვს.

## დაშიფრული სანახის შექმნა

/// details | ვიდეო მაგალითი
        type: success
        open: false


<video controls preload="none" poster="/assets/thumb/vid/bitwarden-create-win.jpg">
    <source src="https://security-media.foi.ge/vid/bitwarden-create-win.mp4" type="video/mp4">
</video>

///

პაროლების მენეჯერი თქვენი მთავარი პაროლით (master password) იშიფრება. 
ამიტომ აუცილებელია, რომ ეს პაროლი რთული და აუცილებლად კომპიუტერის მიერ, შემთხვევითი წესით
გენერირებული იყოს.

ეს იქნება ერთადერთი პაროლი, რომელიც აუცილებლად უნდა დაიმახსოვროთ. 
ამ პაროლის დავიწყების შემთხვევაში, მისი აღდგენა შეუძლებელია და სამუდამოდ
დაკარგავთ წვდომას ინფორმაციაზე, რომელიც მასშია შენახული. ამ რისკის დასაზღვევად, მარტივ და უსაფრთხო 
გადაწყვეტილებას - ინტერნეტთან წვდომის არმქონე მოწყობილობას - ფურცელს გამოვიყენებთ.

ადამიანს რთული პაროლის მოფიქრება არ შეუძლია. მაღალი შემთხვევითობის (random) / ენთროპიის მისაღწევად,
შეგვიძლია გამოვიყენოთ გენერატორი, რომელიც მარტივად დამახსოვრებად, მაგრამ რთულად გამოსაცნობ პაროლს მოგვცემს.

პაროლებისთვის, რენდომულობას / ენთროპიას **ბიტებით** ვზომავთ. 

მარტივად - რაც უფრო მაღალია ეს მაჩვენებელი, მით უფრო უსაფრთხოა თქვენი პაროლი.

/// admonition | მინიმალური სიმძლავრე - 65 ბიტი
    type: warning
პაროლების მენეჯერის პაროლი უნდა იყოს მინიმუმ 65 ბიტი სირთულის მქონე!
///


### პაროლის სირთულის ცხრილი *

Bitwarden Passphrase ან FOI Passphrase (მუდმივი სიმბოლოთი გამოყოფილი - წერტილი, ტირე, ციფრი და სხვ.):

<div class="grid cards" markdown>

- Bitwarden Passphrase (გრძელი სიტყვები)


    მაგალითი: 

    *`peddling.snide.capricorn.equipment`*

    ---
        
    | მეთოდი   | ბიტი (სირთულე)       |
    |----------|----------------------|
    | 4 სიტყვა | :material-close: 52  |
    | 5 სიტყვა | :material-check: 65  |
    | 6 სიტყვა | :material-check: 78  |
    | 7 სიტყვა | :material-check: 90  |
    | 8 სიტყვა | :material-check: 103 |


- [FOI პაროლების გენერატორი](../tools/password-generator.md) (მოკლე სიტყვები)


      მაგალითი:

      *`8bronco slur hat opt`*

    ---
    
    | მეთოდი             | ბიტი (სირთულე)        |
    |--------------------|-----------------------|
    | 4 სიტყვა + 1 ციფრი | :material-close:  55  |
    | 5 სიტყვა           | :material-check:  65  |
    | 6 სიტყვა           | :material-check:  78  |
    | 7 სიტყვა           | :material-check:  91  |
    | 8 სიტყვა           | :material-check:  104 |

</div>


\* *გამოთვლებისთვის გამოყენებულია სიტყვების ბაზები:*
  - *Bitwarden სიტყვების ბაზა: 7776 სიტყვა*
  - *FOI სიტყვების ბაზა: 8509 სიტყვა*

**შენიშვნა:** როგორც ცხრილში ჩანს, სიძლიერეში განსხვავება თითქმის არ არის. 
მთავარი განსხვავება მათ პრაქტიკულობაშია:

<div class="grid cards" markdown>

- FOI პაროლების გენერატორი

    ---
    - შეყვანა უფრო სწრაფია
    - აუცილებელია Bitwarden-ში ხელით გადატანა


- Bitwarden Passphrase

    ---
    - შეყვანას მეტი დრო სჭირდება
    - Bitwarden თავად აგენერირებს

</div>

/// admonition | რეკომენდაცია
    type: tip

- **ხშირად გამოსაყენებელი პაროლებისთვის:** მარცვლების გამოყენება უკეთესია ისეთი პაროლებისთვის, 
  რომელთა ხშირი შეყვანაც გიწევთ (მაგ. მობილურის პაროლი), სადაც გრძელი პაროლის შეყვანა შედარებით რთულია.

- **პაროლების მენეჯერისთვის:** სიტყვების გამოყენება უმჯობესია, რადგან მისი შეყვანა არც ისე
    ხშირად მოგიწევთ და უფრო სწრაფად დაიმახსოვრებთ.

- **საიტებისთვის:** ჩვეულებრივი პაროლი, მინ, 14 სიგრძის, რომელსაც Bitwarden დააგენერირებს და ავტომატურად შეიყვანს.
    მისი დამახსოვრება ან ხელით შეყვანა არასდროს მოგიწევთ. მაგ. `lxKU$db?3;g.ZL`

///

### პაროლების მენეჯერის პაროლის მოფიქრება

პაროლების მენეჯერი ანგარიშის შექმნის შემდეგ, ყველა პაროლს ავტომატურად დაგვიგენერირებს, როგორც
სრულად შემთხვევითი სიმბოლოების ერთობას საიტებისთვის, ისევე დამახსოვრებად სიტყვებსაც.
თუმცა, სანამ პაროლების მენეჯერი გვექნება, აუცილებელია მისი საკუთარი პაროლის მოფიქრებაც, რომელიც ასევე
შემთხვევითი წესით უნდა იყოს გენერირებული. [FOI უფასო გენერატორს](../tools/password-generator.md?os=bitwarden) გთავაზობთ,
რომელიც შეგიძლიათ გამოიყენოთ მანამ, სანამ მენეჯერზე წვდომა გექნებათ.

გახსოვდეთ, რომ ეს პაროლი ძალიან მნიშვნელოვანია! ის იცავს ყველა თქვენს სხვა პაროლს, 
ამიტომ მისი სიძლიერე კრიტიკულად მნიშვნელოვანია თქვენი უსაფრთხოებისთვის.

/// admonition | ადამიანის შექმნილი პაროლების სისუსტე
    type: info

**ადამიანს არ შეუძლია ჭეშმარიტად შემთხვევითი ინფორმაციის გენერირება.**

- **უნიკალურობის ილუზია** - 
   ნებისმიერი სიტყვა ან მათი კომბინაცია, რასაც თქვენ მოიფიქრებთ - ნამდვილი თუ გამოგონილი - 
   არ არის ისეთი უნიკალური, როგორიც გგონიათ.
- **კომპიუტერის მიერ გენერირებული** შემთხვევითი პაროლის სიძლიერე ფასდება ზუსტი მათემატიკური ფორმულით.
- **ადამიანის მიერ მოფიქრებული** პაროლი ეფუძნება პირად გამოცდილებას, ინტერესებს და სხვა ცხოვრებისეულ დეტალებს.
    **მისი სირთულის გამოთვლა შეუძლებელია.**

უსაფრთხოების თვალსაზრისით, ასეთი პაროლი შეიძლება მივიჩნიოთ **0 ბიტის სიძლიერის მქონედ**, 
ანუ პაროლად, რომელიც **1 წამზე ნაკლებ დროში გატყდება**.

///

#### პაროლის გენერირება

- - **[FOI პაროლების გენერატორით](../tools/password-generator.md?os=bitwarden)** დააგენერირეთ **Bitwarden** ტიპის პაროლი, 
    ჩასვით **Bitwarden**-ის ჩანაწერში **Password** ველში.
- ჩაიწერეთ დაგენერირებული პაროლი **ფურცელზე**!
    - არ გადაუღოთ სურათი
    - არ დაასკანეროთ
    - არ გაუზიაროთ არავის (არც საკუთარ თავს მაგ. note to self-ით)
    - არ შეინახოთ ფაილში
    - არ ჩაწეროთ არსად, Bitwarden-ის გარდა.

- ფურცელი შეინახეთ და გაუფრთხილდით იქამდე, სანამ პაროლს არ დაიმახსოვრებთ. პაროლის დამახსოვრების შემდეგ, ფურცელი დაწვით.
- სიტყვებს შორის გამოყოფის გამოყენება მნიშვნელოვანია!
    - არ აქვს მნიშვნელობა, გამოყოფად რას აირჩევთ. ეს შეიძლება იყოს წერტილი, მძიმე, "სფეისი", ციფრი.
   
        მაგ. `primrose.provide.uranus.contrite.raggedy`, ან `primrose provide uranus contrite raggedy` (**არ გამოიყენოთ მაგალითებში მოყვანილი პაროლი!**)


ამ პაროლს გამოიყენებთ პაროლების მენეჯერის დასაშიფრად და გასახსნელად.

/// admonition | მენეჯერის პაროლის აღდგენა შეუძლებელია!
    type: danger
არ დაგავიწყდეთ თავად პაროლების მენეჯერის პაროლი. მისი აღდგენა შეუძლებელი იქნება.

აუცილებლად შეინახეთ ის ფურცელზე იქამდე, სანამ არ დაიმახსოვრებთ.
///

### პაროლების მენეჯერის ბაზის შექმნა

1. გადმოწერეთ და დააინსტალირეთ აპლიკაცია - [https://bitwarden.com/download/#downloads-desktop](https://bitwarden.com/download/#downloads-desktop){:target="_blank"}
2. **Create Account**
3. **E-mail address** - შეიყვანეთ თქვენი ელ. ფოსტა
4. **Master Password** - შეიყვანეთ ფურცელზე ჩაწერილი პაროლი
5. **Master Password Hint** - არ ჩაწეროთ არაფერი!

## Bitwarden პარამეტრები

მაქსიმალური უსაფრთხოებისთვის და კომფორტისთვის, გამოიყენეთ ქვემოთ მოყვანილი პარამეტრები.


### Desktop

შედით პარამეტრებში -  :simple-bitwarden: **Bitwarden > Settings**

| სექცია           | პარამეტრი                                        | მნიშვნელობა                                                  |
|------------------|--------------------------------------------------|--------------------------------------------------------------|
| **Security**     |                                                  |                                                              |
|                  | **Vault Timeout**                                | `On system lock`                                             |
|                  | **Vault timeout action**                         | `Lock`                                                       |
|                  | **Unlock with PIN**                              | :x: :exclamation: :exclamation: :exclamation:                |
|                  | **Unlock with Touch ID / Windows Hello**         | :white_check_mark:                                           |
|                  | **Require password or PIN on app start**         | :white_check_mark: :exclamation: :exclamation: :exclamation: |
|                  | **Approve login requests**                       | :x:                                                          |
| **Preferences**  |                                                  |                                                              |
|                  | **Minimize when copying to clipboard**           | :x:                                                          |
|                  | **Clear clipboard**                              | `30 Seconds`                                                 |
| **App Settings** |                                                  |                                                              |
|                  | **Show menu bar icon**                           | :white_check_mark:                                           |
|                  | **Minimize to menu bar**                         | :white_check_mark:                                           |
|                  | **Close to menu bar**                            | :white_check_mark:                                           |
|                  | **Start to menu bar**                            | :white_check_mark:                                           |
|                  | **Start automatically on login**                 | :white_check_mark:                                           |
|                  | **Always show in the Dock**                      | :white_check_mark:                                           |
|                  | **Allow browser integration**                    | :white_check_mark:                                           |
|                  | **Require verification for browser integration** | :x:                                                          |
|                  | **Use hardware acceleration**                    | :white_check_mark:                                           |


### ბრაუზერი

/// details | ვიდეო მაგალითი
        type: success
        open: false


<video controls preload="none" poster="/assets/thumb/vid/bitwarden-chromium.jpg">
    <source src="https://security-media.foi.ge/vid/bitwarden-chromium.mp4" type="video/mp4">
</video>

///

1. დააყენეთ ბრაუზერის გაფართოება - [https://bitwarden.com/download/#downloads-web-browser](https://bitwarden.com/download/#downloads-web-browser){:target="_blank"}
2. აირჩიეთ დაყენებული გაფართოება და დაპინეთ (Chrome/Brave - მარჯვენა კლიკი > Pin)

ბრაუზერის გაფართოების პარამეტრები:

**Browser** > :simple-bitwarden: **Bitwarden** > **Settings** > **Account Security**

| პარამეტრი                  | მნიშვნელობა                                    |
|----------------------------|------------------------------------------------|
| **Unlock with biometrics** | :white_check_mark:                             |
| **Unlock with PIN**        | :x: :exclamation: :exclamation:  :exclamation: |
| **Vault timeout**          | `1 minute`                                     |
| **Vault timeout action**   | `Lock`                                         |

### Android/iOS

1. დააინსტალირეთ აპლიკაცია - [https://bitwarden.com/download/#downloads-mobile](https://bitwarden.com/download/#downloads-mobile){:target="_blank"}
2. აირჩიეთ Bitwarden პაროლების მთავარ აპლიკაციად

/// tab | Android

- :material-cog: **Settings** > **Passwords, passkeys & autofill** > **Preferred service** > **Bitwarden**
- **Additional services** - გათიშეთ ყველა სხვა.

///

/// tab | iOS

- :material-cog: **Settings** > **Passwords**> **Password options**
- **Keychain** :fontawesome-solid-toggle-off:
- **Bitwarden** :fontawesome-solid-toggle-on:
- გათიშეთ ყველა სხვა ჩამოთვლილი, Bitwarden-ის გარდა.

///

- გამართეთ უსართხოების პარამეტრები **Bitwarden** > **Settings** > **Account Security**:

/// admonition
    type: warning

**Bitwarden**-ს ერთი მნიშვნელოვანი ნაკლოვანება აქვს: მობილურ მოწყობილობებზე, ბიომეტრიული
აუთენტიფიკაციის ჩართვის შემდეგ, სანახის გასახსნელად, ის პაროლს აღარასდროს მოგთხოვთ და ყოველთვის 
ბიომეტრიით შეხვალთ. ამით თითქმის გარანტირებულია, რომ Bitwarden-ის პაროლს ვერასდროს დაიმახსოვრებთ
და ეს პაროლი ფურცელზე მუდამ იარსებებს, რაც რისკებს ზრდის. 

ამიტომ უკეთესია, თუ პირველი 2-3 კვირის განმავლობაში, ან იქამდე, სანამ პაროლს ნამდვილად არ 
დაიმახსოვრებთ, **Bitwarden**-ში ბიომეტრიულ აუთენტიფიკაციას არ გამოიყენებთ.

///

**პარამეტრები**:

<div class="grid cards" markdown>

- **პაროლის დამახსოვრებამდე**

    ---
    
    | პარამეტრი                  | მნიშვნელობა                                 |
    |----------------------------|---------------------------------------------|
    | **Unlock with biometrics** | :x: :exclamation:                           |
    | **Unlock with PIN code**   | :x: :exclamation::exclamation::exclamation: |
    | **Session timeout**        | `1 hour`                                    |
    | **Vault timeout action**   | `Lock`                                      |


- **პაროლის დამახსოვრების შემდეგ**

    ---

    | პარამეტრი                  | მნიშვნელობა                                 |
    |----------------------------|---------------------------------------------|
    | **Unlock with biometrics** | :white_check_mark:                          |
    | **Unlock with PIN code**   | :x: :exclamation::exclamation::exclamation: |
    | **Session timeout**        | `15 minutes`                                |
    | **Vault timeout action**   | `Lock`                                      |

</div>


## პაროლების იმპორტი

გადაიტანეთ ბრაუზერში და ოპერაციულ სისტემებში შენახული პაროლები პაროლების მენეჯერში.
კარგი იქნება, თუ ასეთი პაროლებისთვის **Bitwarden**-ში ცალკე საქაღალდეს შექმნით. ამ გზით,
პაროლები მხოლოდ ერთ სივრცეში გექნებათ და გეცოდინებათ, რომელი პაროლებია შესაცვლელი, ხოლო რომელი
- Bitwarden-ის მიერ გენერირებული.

### Google Chrome-დან

- გამოიყენეთ ინსტრუქციები [Bitwarden-ის საიტზე](https://bitwarden.com/help/import-from-chrome/){:target="_blank"}
- დარწმუნდით, რომ ყველა პაროლი წარმატებით დაიმპორტდა პაროლების მენეჯერში
- იმპორტის დასრულების შემდეგ, წაშალეთ პაროლები ბრაუზერიდან:
    - Chrome-ში დააჭირეთ :fontawesome-solid-ellipsis-vertical: > **Delete Browser Data** > **Advanced**
    - Time Range-ში მიუთითეთ **All time**
    - მონიშნეთ **Passwords and other sign-in data**
    - დააჭირეთ ღილაკს **Delete Data**

### Apple- მოწყობილობებიდან

iPhone-ში შენახული პაროლების ექსპორტი ტელეფონიდან შეუძლებელია. ამისთვის დაგჭირდებათ
macOS.

- გამოიყენეთ Safari-ს ინსტრუქციები [Bitwarden-ის საიტზე](https://bitwarden.com/help/import-from-safari/){:target="_blank"}
- დარწმუნდით, რომ ყველა პაროლი წარმატებით დაიმპორტდა პაროლების მენეჯერში
- იმპორტის დასრულების შემდეგ, წაშალეთ პაროლები ყველა მოწყობილობიდან
    - iPhone: **Settings** > **Passwords**, პაროლების ჩამონათვალში 2 თითით ჩამოსქროლეთ, აირჩიეთ ყველა პაროლი და დააჭირეთ **Delete**.
    - macOS: **Safari** > **Settings** > **Passwords** > მონიშნეთ ყველა პაროლი და დააჭირეთ **Delete**.

## პრობლემების მოგვარება

### ბიომეტრიული აუთენტიფიკაცია macOS-ზე

Bitwarden-ში არსებული [ხარვეზის](https://github.com/bitwarden/clients/issues/5591){:target="_blank"} გამო, თუ ლეპტოპს დახურავთ, ხელახლა გახსნისას ბიომეტრიული აუთენტიფიკაციის ოფცია არ გამოჩნდება.

დროებითი გამოსავალი:

1. Bitwarden-ის აუთენტიფიკაციის ეკრანზე დააჭირეთ კლავიშების კომბინაციას: ++cmd+l++
2. ამის შემდეგ "Unlock with Touch ID" ღილაკი უნდა გამოჩნდეს.

ეს პრობლემა მხოლოდ ლეპტოპის დახურვით დაბლოკვისას ჩნდება და მოგვარდება Bitwarden-ის მომავალ განახლებებში.


## შემდეგი ნაბიჯები

- [x] შეცვალეთ მთავარი პაროლები Bitwarden-ის მიერ გენერირებული პაროლით და შეინახეთ მენეჯერში
    * მაგ. Apple ID, Google, Facebook
- [x] გააგრძელეთ მრავალბიჯიანი აუთენთიფიკაციით:

<div class="grid cards" markdown>

- [:material-two-factor-authentication: მრავალბიჯიანი აუთენტიფიკაცია](mfa.md)
</div>