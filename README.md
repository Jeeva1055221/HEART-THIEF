
###

<p align="center"><img align="center" height="400" src="https://telegra.ph/file/4685c87a5ded60d7752eb.jpg"/>

###

```python3
import datetime
import pytz
from motor.motor_asyncio import AsyncIOMotorClient
from info import *

client = AsyncIOMotorClient(DATABASE_URI)
mydb = client[DATABASE_NAME]

class Database():
    def __init__(self):
        self.name = ['⌯ Ꭺɴᴏɴʏᴍᴏᴜꜱ | ×͜× |']
        self.country = ['India']
        self.language = ['Bengali', 'English']

    def new_viewer(self, id, name):
        return dict(
            id = id,
            name = name
            )
        )

    async def add_viewer(self, id, name):
        user = self.new_user(id, name)
        await self.col.insert_one(user)
    
    async def is_viewer_exist(self, id):
        user = await self.col.find_one({'id':int(id)})
        return bool(user)
    
    async def total_viewer_count(self):
        count = await self.col.count_documents({})
        return count 

db = Database()
```

###

&nbsp;   &nbsp;  ![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=ʙᴀᴍ+ʙʜᴏʟᴇ+😊;ᴡᴇʟᴄᴏᴍᴇ+ᴛᴏ+ᴍʏ+ᴘʀᴏꜰɪʟᴇ.;ʙᴏʟᴏ+ʜᴀʀ+ʜᴀʀ+ᴍᴀʜᴀᴅᴇᴠ.)

###

<div align="center">
<br><p align="center"><b>ᴘʀᴏꜰɪʟᴇ ᴠɪᴇᴡᴇʀꜱ</b></p>  
<p align="center"><img align="center" src="https://profile-counter.glitch.me/{NBBotz}/count.svg"/></p> 

<img src="https://github.com/NBBotz/NBBotz/blob/main/items/analytics.webp" width="57px" style="float: left; margin-right: 10px;">
<h1>ꜱᴛᴀᴛɪꜱᴛɪᴄᴀʟ ᴅᴀᴛᴀ'ꜱ</h1>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=NBBotz&show_icons=true&line_height=37&locale=en&bg_color=0d1117&text_color=ffffff"
       alt="ɢɪᴛʜᴜʙ ꜱᴛᴀᴛꜱ" />  
</p>



