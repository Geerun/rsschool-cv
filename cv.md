_CV (Curriculum Vitae)_


![_Geerun_](avatar.png) 

# Eugene Doroshenko (Geerun)
## Frontend Developer

> Date of Birth: December '82 
> 
> Nationality: Russian Federation
> 
> Educational Qualification: College Graduate 2002


## Contacts

**Email**: _bestgeerun@gmail.com_

**Cellphone**: _+79270033093_

**GitHub**: ![_Geerun_](https://github.com/Geerun)  ![Gitcathub](https://github.githubassets.com/images/icons/emoji/octocat.png)


## Me

### Skills
   * HTML
   * CSS
   * JavaScript
   * Git      
   * English. Good reading and translating ability
    
### Objective

   Change the current position. Become a Web developer. Change my life.

## Code example

### The Collatz hypothesis (In Pascal)
```pascal 
program collatz;
{$APPTYPE CONSOLE}
uses
  SysUtils, Classes;
var
   s: string;
   num, steps, max: integer;   
begin
   readln(s);
   num:=strtoint(s);  // original number
   steps:=0;          // step counter
   max:=num;          // maximum intermediate number
   while (num<>1) do
   begin
      if odd(num) then num:=num*3+1  // The number is odd
      else num:=num div 2;           // The number is even
      if num>max then max:=num;
      inc(steps);
      writeln(inttostr(num));
   end;
   writeln('Steps - '+inttostr(steps));
   writeln('Max - '+inttostr(max));
end.

```

* * *

```

   Be a Person. Not a Resumé.
            
            ~ Sharad Vivek Sagar

```
