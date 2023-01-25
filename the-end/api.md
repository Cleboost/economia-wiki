# Api

Une api est en cours de développement... Elle pourrait par exemple permettre a d'autre bot ou site d'avoir accès aux données de Economia en lecture seul comme par exemple voir l'argent sur le compte, les médailles...

{% swagger method="get" path="" baseUrl="https://api.economia.cleboost.ovh/users/{id}/money" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="id" type="DISCORD_ID" required="true" %}
L'id de l'utilisateur discord
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
    money: 0
}
```
{% endswagger-response %}
{% endswagger %}
