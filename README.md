# 01101000 01100101 01101100 01101100 01101111  👋

```Shell
from django.views.generic.detail import DetailView

class AboutMe(DetailView):
  name = "Mohamed E.Faleh"
  location = "Qabis, Tunisia"
  education = "Computer Science"
  website = "Elfalehdev.github.io"
  
   #get social media links
  def get_social_contact(self):
    social_media_links = {
      "facebook": "facebook.com/elfalehdev"
      "instagram": "instagram.com/elfalehdev"
      "twitter": "twitter.com/elfalehdev"
    }    
    return social_media_links 
  
  #get all my favorite  programming languages
  def get_fav_lang(self):
      languages = ['python 🐍 ', 'javascript😺 ', 'C++❤️']
      return languages
      
  #get all my favorite frameworks
  def get_fav_frameworks(self):
    frameworks = ['django 🔫 ', 'react 🎯', 'bootstrap✨' ]
    return frameworks
   
  #get the databases that i can use
  def get_databases(self):
   data_bases = ['mysql 👍', 'mongodb 🍃']
   return data_bases
   
   #current repositories I am working on 
   def get_current_repos(self): 
    repos = ['noahark', 'mush', 'RTLT', 'RPdevtools', 'fridayos', 'ReactDailyPlanner']
    return repos 
   
     
   ```
 
