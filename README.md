ERB-Sublime-Snippets
====================

This repo is fork from git://github.com/matthewrobertson/ERB-Sublime-Snippets.git for personal erb syntax, like <%= link_to(, )%> instead of <%= link_to , >, which is the convension from master XDite master Yung.


### For OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    $ git clone git://github.com/jeffrey410469/ERB-Sublime-Snippets.git ERB_Snippets

### For Windows

    $ cd %APPDATA%/Sublime Text 2/Packages/
    $ git clone git://github.com/jeffrey410469/ERB-Sublime-Snippets.git ERB_Snippets

### For Linux

    $ cd ~/.Sublime Text 2/Packages/
    $ git clone git://github.com/jeffrey410469/ERB-Sublime-Snippets.git ERB_Snippets

##Snippets and Bindings

<table>
  <tr>
    <th>Snippet</th>
    <th>Tab Trigger</th>
    <th>Output</th>
  </tr>
  <tr>
    <td>ERB tags</td>
    <td>__er__</td>
    <td>`<%  %>`</td>
  </tr>
  <tr>
    <td>print ERB tags</td>
    <td>__pe__</td>
    <td>`<%=  %>`</td>
  </tr>
  <tr>
    <td>print ERB comment</td>
    <td>__pc__</td>
    <td>`<%#  %>`</td>
  </tr>
  <tr>
    <td>`if` block</td>
    <td>__if__</td>
    <td>`<% if  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`if` / `else` block</td>
    <td>__ife__</td>
    <td>`<% if  %>...<% else %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`else` tag</td>
    <td>__else__</td>
    <td>`<% else %>`</td>
  </tr>
  <tr>
    <td>`elsif` tag</td>
    <td>__elsif__</td>
    <td>`<% elsif %>`</td>
  </tr>
  <tr>
    <td>`unless` block</td>
    <td>__unless__</td>
    <td>`<% unless  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`end` block</td>
    <td>__end__</td>
    <td>`<% end %>`</td>
  </tr>
  <tr>
    <td>`submit_tag` helper</td>
    <td>__st__</td>
    <td>`<%= submit_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`text_field_tag` helper</td>
    <td>__tft__</td>
    <td>`<%= text_field_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`password_field_tag` helper</td>
    <td>__pft__</td>
    <td>`<%= password_field_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`label_tag` helper</td>
    <td>__lblt__</td>
    <td>`<%= label_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`link_to` helper</td>
    <td>__lt__</td>
    <td>`<%= link_to (, ) %>`</td>
  </tr>
  <tr>
    <td>`form_for` helper</td>
    <td>__form__</td>
    <td>`<%= form_for(@ ) do |f| %> ... <% end %>`</td>
  </tr>
  <tr>
    <td>`t()` helper</td>
    <td>__t__</td>
    <td>`<%= t('@') %>`</td>
  </tr>
<table>

##Questions, Comments, Concerns?

Feel free to submit a pull request with any snippets you would like to add to the project. If you have any problems or suggestions you can contact me [on twitter](https://twitter.com/mattdrobertson).

##License

Released under [WTFPL, Version 2](https://raw.github.com/matthewrobertson/ERB-Sublime-Snippets/master/LICENSE.txt)