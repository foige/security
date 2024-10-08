---
title: კომუნიკაცია
icon: material/chat
---

# კომუნიკაცია

## წინასწარ შესასრულებელი ნაბიჯები

- [x] [პაროლების მენეჯერი](passwords.md)

## რეკომენდირებული კომუნიკაციის საშუალება

<div class="grid cards" markdown>

- ![Signal](../assets/img/logo/signal.svg){ .lg .middle .twemoji } [Signal](https://signal.org/download/){:target="_blank"}

    ---
    **Signal** არის ყველაზე უსაფრთხო კომუნიკაციის საშუალება. სიგნალი მომხმარებლის შესახებ
    მხოლოდ მინიმალურ ინფორმაციას ინახავს და ყველა კომუნიკაცია ბოლოდან ბოლომდე დაშიფრულია (E2EE). 
    ეს ნიშნავს, რომ თქვენს კომუნიკაციაზე წვდომა მხოლოდ თქვენ და თქვენს ადრესატს გაქვთ.
    იმ შემთხვევაშიც კი, თუ სახელმწიფო სიგნალისგან თქვენზე მონაცემებს მოითხოვს, სიგნალს
    არაფერი აქვს და შესაბამისად, ვერაფერს მიაწვდის.

</div>

## დამატებითი უსაფრთხოება

### რეგისტრაციის დაბლოკვა

იქიდან გამომდინარე, რომ სიგნალი რეგისტრაციისთვის მობილურ ნომერს იყენებს, ბოროტმოქმედებს
შესაძლებლობა აქვთ, მოგპარონ ნომერი და თქვენი ნომრით გაიარონ რეგისტრაცია. ამის პრევენციისთვის
აუცილებელია რეგისტრაციაზე პაროლის დაყენება.

1. Bitwarden-ში დააგენერირეთ 5-სიტყვიანი პაროლი და შეინახეთ. დაარქვით სახელი, მაგ. "Signal PIN"
2. Signal-ში გადადით :material-dots-vertical: > **Settings** > **Account** > **Signal PIN**
3. დააჭირეთ **Create PIN** ან **Change PIN** და შეიყვანეთ დაგენერირებული პაროლი
4. - [x] ჩართეთ "Registration Lock"

ამის შემდეგ, სიგნალის ხელახლა დაყენების შემთხვევაში, ნომრის ვერიფიკაციასთან ერთად მოგიწევთ
ამ პაროლის შეყვანაც. სხვა პირებისთვის თქვენი ნომრით რეგისტრაციის გავლა ამ პაროლის გარეშე
მხოლოდ იმ შემთხვევაში იქნება შესაძლებელი, თუ 7 დღის განმავლობაში ნომერი არცერთ მოწყობილობაზე
არ იქნება აქტიური.

### მობილური ნომრის დაფარვა

Signal-ში შესაძლებელია მობილური ნომრის ნაცვლად მომხმარებლის სახელების (username) გამოყენება.
მომხმარებლის სახელის დაყენების შემთხვევაში, იმ პირებისთვის, ვისთანაც კომუნიკაცია გაქვთ, თქვენი ნომერი
ხელმისაწვდომი იქნება მხოლოდ მაშინ, თუ მათ კონტაქტებში დამატებული ჰყავხართ.

1. Signal-ში გადადით :material-dots-vertical: > **Settings** > **დააჭირეთ სახელს ან სურათს**
2. **@** სიმბოლოს გვერდით შეიყვანეთ თქვენი სასურველი მომხმარებლის სახელი
3. Signal-ში გადადით :material-dots-vertical: > **Settings** > **Privacy** > **Phone Number** და დააყენეთ:

    Who can see my phone number:

     - **Nobody**
   
    Who can find me by number:

     - **Nobody**

4. მობილური ნომრის გაზიარების ნაცვლად, გააზიარეთ თქვენი უნიკალური მომხმარებლის სახელი.

### მესიჯების ავტომატური წაშლა

მიუხედავად იმისა, რომ სიგნალის მესიჯები ბოლოდან ბოლომდე დაშიფრულია, ეს მესიჯები მაინც ინახება
მოწყობილობაზე. იმ შემთხვევაში, თუ თქვენს ან თქვენი ადრესატის მოწყობილობაზე ვინმემ წვდომა მოიპოვა,
თქვენი მესიჯები მათთვის ხელმისაწვდომი გახდება.

მესიჯების ავტომატური წაშლით, მესიჯები წაიშლება დაყენებული დროის გასვლის შემდეგ. დროის ათვლა დაიწყება მას შემდეგ, რაც ადრესატი წაიკითხავს მესიჯს.

1. Signal-ში გადადით :material-dots-vertical: > **Settings** > **Privacy** > **Disappearing messages**
2. აირჩიეთ 1 კვირა

ამის შემდეგ, ყველა ახლად დაწყებულ ჩატში გაგზავნილი ან მიღებული მესიჯები 1 კვირაში წაიშლება ყველა
მოწყობილობიდან.

იმ შემთხვევებში, როდესაც სასურველია მესიჯების ისტორიის უფრო ხანგრძლივი ვადით შენახვა ან ავტომატური
წაშლის საერთოდ გათიშვა, კონკრეტული ჩატის პარამეტრებიდან შეგიძლიათ ეს შეცვალოთ.

### იდენტობის ვერიფიკაცია

დარწმუნდით, რომ პირი, ვისაც ესაუბრებით, ნამდვილად ისაა, ვინც გგონიათ. არსებობს რისკი, რომ
ვინმე თქვენთვის ცნობილი პიროვნების იდენტობის მითვისებას ეცდება. ამის თავიდან ასაცილებლად შემდეგი გზა გაქვთ:

1. პიროვნებასთან შეხვედრისას (სასურველია პირისპირ, მაგრამ უკიდურეს შემთხვევაში - ვიდეოზარით), დაიწყეთ მასთან კომუნიკაცია Signal-ის ჩატის მეშვეობით.
2. ორივე მოწყობილობაზე, Signal-ის ჩატში გადადით :material-dots-vertical: > **View safety number**
3. შეადარეთ ნომრები და თუ ისინი ემთხვევა, მონიშნეთ "Mark as verified"

იმ შემთხვევაში, თუ ვინმე ამ კომუნიკაციის "შუაში ჩაჯდა", ან დარეგისტრირდა პირის ნომრით სხვა მოწყობილობაზე,
ეს ნომერი შეიცვლება და კონტაქტს ავტომატურად მოეხსნება ვერიფიკაცია.

არასდროს ენდოთ ახალ კონტაქტს მანამ, სანამ მის იდენტობას არ დაადასტურებთ. Signal არ ამოწმებს
პიროვნებების სახელებს და, შესაბამისად, ნებისმიერს შეუძლია დაირქვას ის, რაც მას სურს.