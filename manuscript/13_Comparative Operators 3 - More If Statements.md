# Comparative Operators 3 - More If Statements

<table>
<tbody>
  <tr>
    <td class="tg-0lax" colspan="2">If statements can check for a list of things instead of just 1. For example:
</td>
  </tr>
<tr>
<td> 

```python
temp = int(input("What's the temperature in celcius?"))

if temp < 8:
    print("Brr, its a cold day!!!")
elif temp >= 8 and temp < 15:
    print("I'ts a mild day")
elif temp >= 15  and temp < 21:
    print("Its a warm day")
elif temp >= 21:
    print("It's a hot day")
else:
    print("sorry, you must enter a number")
```

</td>
<td>

Can you see that the command `if` is only used once?

Every other time to check ***if*** something is `True`, Python uses `elif`.

</td>
</tr>
</tbody>
</table>

<table>
<tbody>
  <tr>
    <td colspan="2">Task 1</td>
  </tr>
<tr>
<td> 

Write a programme to check if a user goes by the name of either John, George, Ringo or Paul. If one of those names is True, Python should say:

> `>"Hey that’s the name of a Beatle!"`

If not, Python should say:

> `>"That’s a nice name"`
</td>
</tr>
<tr>
  <td>
    
```
    
    


```

  </td>
</tr>
</tbody>
</table>

<table>
<tbody>
  <tr>
    <td colspan="2">Task 2</td>
  </tr>
<tr>
<td colspan="12"> 

Write a programme to comment on how interesting a football match was. Remember to use the `elif` command several times like in the example above.
* If no goals were scored, Python should say `"the game was a bore draw!"`
* 1-2 goals: `"Not the most interesting game"`
* 3-5 goals: `"It was a very interesting game"`
* 6+ goals: `"The football match was an unmissable game!"`

</td>
</tr>
<tr>
  <td colspan="12">
    
```
    
    
    
    
    
    
    
    
    


```

  </td>
</tr>
</tbody>
</table>
