# Let's crowdsource!

## Step 1

Chose a drama [here](https://github.com/alexdyul/XML_DH?fbclid=IwAR3fR7SUWv7OlIKlyjvO7VUP0HLJlSS-CP7ZzM2OCZPJEWKmo6RJ5Fhc9Jk)

## Step 2

Find the drama on <https://dracor.org/rus>
Look carefully at the cast list. Find characters to code.

## Step 3

Open the TEI-file on GitHub press the button "edit" and start coding!

1. Write type="personal" inside the tag \<listRelation>

2. Add tags \<relation name = ....>

3. Press "Propose file change"

4. Press "Create pull request" and again "Create pull request" -> YOU ARE DONE!

__Here's the overview of types of relations (from our partners in Stuttgart): https://github.com/quadrama/Corpus#relations__

## Example

```
<listRelation type="personal">
            <relation name="parent_of" active="#famusov" passive="#sofija"/>
            <relation name="related_with" active="#hlestova" passive="#famusov"/>
            <relation name="associated_with" active="#molchalin" passive="#famusov"/>
            <relation name="spouses" mutual="#platon_mihajlovich #natalja_dmitrievna"/>
            <relation name="spouses" mutual="#bärbel #adam"/>
            <relation name="spouses" mutual="#knjaz #knjaginja"/>
            <relation name="siblings" mutual="#pervaja_knjazhna #vtoraja_knjazhna #tretja_knjazhna #chetviortaja_knjazhna #pjataja_knjazhna #shestaja_knjazhna"/>
            <relation name="parent_of" active="#knjaz" passive="#pervaja_knjazhna #vtoraja_knjazhna #tretja_knjazhna #chetviortaja_knjazhna #pjataja_knjazhna #shestaja_knjazhna">
            <relation name="parent_of" active="#knjaginja" passive="#pervaja_knjazhna #vtoraja_knjazhna #tretja_knjazhna #chetviortaja_knjazhna #pjataja_knjazhna #shestaja_knjazhna">
\</listRelation>
```
          
          Действующие:
Павел Афанасьевич Фамусов, управляющий в казенном месте.

Софья Павловна, его дочь.

Лизанька, служанка.

Алексей Степанович Молчалин, секретарь Фамусова, живущий у него в доме.

Александр Андреевич Чацкий.

Полковник Скалозуб, Сергей Сергеевич.

Наталья Дмитриевна, молодая дама

Платон Михайлович, муж ее

Горичи.

Князь Тугоуховский и Княгиня, жена его, с шестью дочерями.

Графиня бабушка

Графиня внучка

Хрюмины.

Антон Антонович Загорецкий.

Старуха Хлёстова, свояченица Фамусова.

г. N*.

г. D*.

Репетилов.

Петрушка и несколько говорящих слуг.

Множество гостей всякого разбора и их лакеев при разъезде.

Официанты Фамусова.
