# rsschool-cv

# Alexander Nikitin

![avatar](/images/avatar.jpg)

## PHP Web Backend/Frontend Developer

## Contact info

- **Location:** Russia, Moscow
- **Phone**: +7 909 916 64 21
- **e-mail:** [alexnik.88kam@gmail.com](mailto:alexnik.88kam@gmail.com)
- [**GitHub**](https://github.com/Alexsail8)
- [**Telegram:**](https://t.me/AlexNkitn) @AlexNkitn
- [**Discord:** ](https://discord.com/) Alex Nikitin(@Alexsail8)

## About me

> I'm a Backend and Frontend Developer from Moscow.
> I like to realize myself in the web direction, to show logic and creativity in solving interesting problems, to create interesting, beautiful mechanisms and functionality for pleasant and convenient use by Internet users.

## Skills

Here are few technologies I work with:

- Programming languages:
- Backend: PHP 5.6/7+, MySql, OOP, Laravel, MVC, singleton,
  Ajax, API, XML, JSON.
- Frontend: JavaScript, HTML5, CSS3, SASS, flex, grids,
  Bootstrap, Semantic UI.
- Tools: Git/GitHub, Composer, Gulp, Postman, Adobe Photoshop.

## Experience

I worked as a

- Beckend/Frontend Developer at Ginzzu, Moscow
  10.2016 - till now
- Frontend Developer at Kam-studio, Moscow
  12.2015 - 10.2016

## Education

- 2018 Armavir State Pedagogical University, Armavir -
  Manufacturing and entrepreneurship, Design, Vocational training (by industry)
- 2014 NOU "INTERNATIONAL CENTER FOR VOCATIONAL EDUCATION" -
  WEB - design Programming WEB - sites, Specialist in the development and support of WEB - sites

## Portfolio

- https://ginzzu.ru

## Code example

```
<style>
.checkbox-section {
	width: 200px;
}
.nthColorLight .checkbox-section_field:nth-child(2n+1) {
  background-color: #f1efef;
}

input[type=checkbox] {
  width: 20px;
  height: 20px;
  margin: 7px 15px;
}
</style>
<form action="">
  <div class="checkbox-section nthColorLight">
    <div class="checkbox-section_field">
      <input type="checkbox" class="allcheckbox-js" name="allcheckbox" id="allcheckbox" placeholder="" data-name="allcheckbox" value="Выбрать всё"><label for="allcheckbox" class="label-inline label-inline-checkbox"><span>Выбрать всё</span></label>
    </div>

    <div class="checkbox-section_field">
      <input type="checkbox" name="name1" data-name="allcheckbox" id="name1" placeholder="" value="Item 1">
      <label for="name1" class="label-inline label-inline-checkbox"><span>Item 1</span></label>
    </div>
    <div class="checkbox-section_field">
      <input type="checkbox" name="name2" data-name="allcheckbox" id="name2" placeholder="" value="Item 2">
      <label for="name2" class="label-inline label-inline-checkbox"><span>Item 2</span></label>
    </div>
    <div class="checkbox-section_field">
      <input type="checkbox" name="name3" data-name="allcheckbox" id="name3" placeholder="" value="Item 3">
      <label for="name3" class="label-inline label-inline-checkbox"><span>Item 3</span></label>
    </div>
    <div class="checkbox-section_field">
      <input type="checkbox" name="name4" data-name="allcheckbox" id="name4" placeholder="" value="Item 4">
      <label for="name4" class="label-inline label-inline-checkbox"><span>Item 4</span></label>
    </div>
  </div>
</form>

// multiple selection checkbox items
$(document).on('change', 'input[type=checkbox]', function () {
  var thiss = $(this),
    thiss = thiss[0],

    nameAttr = thiss.getAttribute('data-name'),
    checkedsEl = $('input[data-name="'+nameAttr+'"'),
    all = checkedsEl.filter(".allcheckbox-js");

  if (thiss.classList.contains('allcheckbox-js')) {
    checkedsEl.prop('checked', $(this).prop('checked'));
  }
  else switch (checkedsEl.filter(":checked").length) {
    case +all.prop('checked'):
      all.prop('checked', false).prop('indeterminate', false);
      break;
    case checkedsEl.length - !! $(this).prop('checked'):
      all.prop('checked', true).prop('indeterminate', false);
      break;
    default:
      all.prop('indeterminate', true);
  }
});
```

## Langauges

- Russian - Native
- English - A2
