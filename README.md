### Hey there, I'm [Lucas Lima](https://github.com/luluopa) 👋

```
 
 DATA = {
    languages:['python','java','javascript', 'c', 'c++'],
    frameworks:['django','reactjs','react native'],
    name:'lucas lima',
    email:'luluopa3@gmail.com',
    number:'55 11 973299866'
 }

class Me:
  def __init__(self, *args, **kwargs):
    self.name = kwargs['name']
    self.number = kwars['number']
    self.email = kwargs['email']
    self.languages = kwargs['languages']
  
  def get_listOfAll_languages_i_know(self):
    return self.languages

  def __str__(self):
    return self.name

def main():
  me = Me(DATA)
  
  print(me)
  print('--------------------------------')
  print('languages i know: ', me.get_listOfAll_languages_i_know())
  print('--------------------------------')

if '__main__' == __main__:
    main()

```

<!--
**luluopa/luluopa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
