# Hey there, I'm [Lucas Lima](https://www.linkedin.com/in/lucas-lima-61877a1a3/) 👋

I am a software developer focused in creating web applications, also a little of mobile 

<!-- Socials -->
<a href="https://www.linkedin.com/in/lucas-lima-61877a1a3/"><img src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" title="Linkedin" alt="Lucas Lima Linkedin account" width="20"/></a>
&ensp;<a href="https://www.showwcase.com/denicmarko"><img src="https://www.showwcase.com/favicon.png" title="Showwcase" alt="Marko Denic Showwcase profile" width="30"/></a>
&ensp;<a href="https://github.com/luluopa"><img src="https://cdn.worldvectorlogo.com/logos/github-icon-1.svg" title="GitHub" alt="Lucas Lima GitHub profile" width="30"/></a>
<br>

```
 
DATA = {
    'languages':['python','java','javascript', 'c', 'c++'],
    'frameworks':['django','reactjs','react native'],
    'name':'lucas lima',
    'email':'luluopa3@gmail.com',
    'number':'55 11 973299866'
}

class Me:
    def __init__(self, *args, **kwargs):
        self.name = kwargs.get('name')
        self.number = kwargs.get('number')
        self.email = kwargs.get('email')
        self.languages = kwargs.get('languages')
        self.frameworks = kwargs.get('frameworks')
    
    def split_list_and_send_a_string_with_all_content(self, objs):
        result = str()

        for obj in objs:
            result += obj
            result += ' '

        return result

    def get_allFrameworks_i_know(self):
        return self.split_list_and_send_a_string_with_all_content(self.frameworks)

    def get_allLanguages_i_know(self):
        return self.split_list_and_send_a_string_with_all_content(self.languages)

    def __str__(self):
        return self.name

def main():
    me = Me(
            name=DATA['name'], number=DATA['number'], 
            email=DATA['email'], languages=DATA['languages'],
            frameworks=DATA['frameworks']
            )
    
    print(me)
    print('--------------------------------')
    print('languages i know: ', me.get_allLanguages_i_know())
    print('--------------------------------')
    print('frameworks i know: ', me.get_allFrameworks_i_know())
    print('--------------------------------')

if __name__ == '__main__':
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
