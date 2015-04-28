Search IT-Books and download them.
=====
A sub project of it-books that supports download it-books directly and searching books by name.

###API from project [IT-Books](https://github.com/XinyueZ/itbooks/blob/master/server/download.go)
  
###REST 

###API: http://itbooks-live-release-surge-778.appspot.com/download

###Json body to search a book
```json
{
  "query":"windows 8"
}

```

###Result, status=200(success, otherwise fail).
```json
{
    "status": 200,
    "keyword": "windows 8",
    "count": 29,
    "result": [
        {
            "Name": "Beginning Windows 8 Application Development",
            "Author": "Istvan Novak, Zoltan Arvai, Gyorgy Balassy, David Fulop",
            "Size": "23.4 MB",
            "Pages": "624",
            "Link": "http://tinyurl.com/ml4x63m",
            "ISBN": "978-1-1180-1268-0",
            "Year": "2012",
            "Publisher": "Wrox",
            "CoverUrl": "http://tinyurl.com/kxxw3e9",
            "Description": "If you're a beginning developer, there's no better place to get up to speed on the  windows/ Windows eBooksWindows 8  sdk/ SDK eBooksSDK than this Wrox guide. A team of  microsoft/ Microsoft eBooksMicrosoft experts provides a complete course in Windows 8 programming, helping you take full advantage of the innovative new SDK. Written in an easy-to-read style, this book is packed with reusable examples that showcase the endless possibilities of the Windows SDK and also introduces the new Windows 8 app store.<br>\n<br>\nIt explains how to set up the development environment and covers user interface design, using special effects and graphics, working with C# and C++, and much more."
        },
        ......
   ]
}
```

License
======
```json
			Copyright Xinyue Zhao

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

