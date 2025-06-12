# Human Extending System

Systém slouží ke sběru, správě a vyhodnocení dat z nositelné elektroniky. Je určena pro výzkumné účely a sbírá základní data z nositelné elektroniky. Aplikace umožňuje uživatelskou autentizaci, správu dat a odesílání notifikací (ve vývoji).
---

## Cílová skupina

V jednotlivých verzích je určena pro primárně jinou cílovou skupinu a toto použití je v souladu s prostředím, kde je provozována.
1. Pro výzkumné účely (externí) - primárně určena výzkumníkům - nasazení na Heroku v kombinaci s daty uloženými na vlastním serveru
2. Pro tělocvikáře a výzkumné účely - provoz ve vnitřním systému UO - primárně pro hodnocení a sběr dat od studentů a výzkumů prováděných na Univerzitě Obrany
3. Pro potřeby AČR a statistické zpracování dat - provoz ve vnitřních systémech rezortu MO.

> Veškeré použití lze upravovat na základě požadavků. Možnosti využití v oblasti telemedicíny, rehabilitace, preventivní medicíně.

### Role a názvosloví

- **Zařízení (jedinec):** nositelná elektronika (např. Garmin) přiřazená konkrétnímu jedinci (ten nemusí mít do samotné aplikace přístup, slouží jen ke sběru dat)
    
- **Uživatel (supervizor):** odborný uživatel s přístupem k vybraným skupinám jedinců (má práva nahlížet na svou skupinu, editovat v rámci jedinců ve skupině. Nemůže přidávat nové jedince.)
    
- **Administrátor (superuser):** má přístup ke správě skupin, zařízení i přiřazení jedinců k uživatelům.

  
[Link to another page](./another-page.html).

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### **🔧 Technologie**

| **Komponenta**  | **Použité technologie**       |
| --------------- | ----------------------------- |
| Backend         | Django 5.1.7, Python 3.11     |
| Databáze        | MySQL, PostgreSQL             |
| Frontend        | Django templates, Bootstrap 5 |
| Nasazení        | Heroku                        |
| E-maily         | Resend / SMTP                 |
| Autentizace     | Django (s registrací)         |
| API (volitelně) | Django REST Framework         |

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
