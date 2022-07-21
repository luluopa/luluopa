# Hey there, I'm [Lucas Lima](https://www.linkedin.com/in/lucas-lima-61877a1a3/) 👋

I am a software developer and that is it. 

<!-- Socials -->
<a href="https://www.linkedin.com/in/lucas-lima-61877a1a3/"><img src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" title="Linkedin" alt="Lucas Lima Linkedin account" width="20"/></a>
&ensp;<a href="https://luluopa.showwcase.com/"><img src="https://www.showwcase.com/favicon.png" title="Showwcase" alt="Lucas Lima Showwcase profile" width="20"/></a>
&ensp;<a href="https://github.com/luluopa"><img src="https://cdn.worldvectorlogo.com/logos/github-icon-1.svg" title="GitHub" alt="Lucas Lima GitHub profile" width="20"/></a>
<br>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=luluopa" alt="luluopa" /></a> </p>

<h3>Most used languages</h3>
<p>
<img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=luluopa&show_icons=true&locale=en&layout=compact" alt="luluopa" /></p>
<p>&nbsp;
<img align="center" src="https://github-readme-stats.vercel.app/api?username=luluopa&show_icons=true&locale=en" alt="luluopa" />
</p>

```python
 
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
