# Titanic-Dataset
Assignment to display name and age of passengers

## Display Name and Age of Passengers

The following structure shows the name and ages of passengers on the Titanic when it sailed.

{% for anyword in site.data.titanic %}

-  {{anyword.Name}}: {{anyword.Age}}

{% endfor %}
