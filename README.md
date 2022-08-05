# simpledrawer

### Sample Drawer For Practise


```
drawer: Drawer(
        child: Container(
          color: Colors.deepPurple[200],
          child: ListView(
            children: [
              DrawerHeader(
                child: Center(
                  child: Text(
                    'L O G O ',
                    style: TextStyle(fontSize: 37),
                  ),
                ),
              ),
              ListTile(
                leading: Icon(Icons.home),
                title: Text(
                  'Page 1',
                  style: TextStyle(fontSize: 20),
                ),
                onTap: (){
                  Navigator.of(context).push(MaterialPageRoute(builder: (context)=> FirstPage()));
                },
              ),

              ListTile(
                leading: Icon(Icons.home),
                title: Text(
                  'Page 2',
                  style: TextStyle(fontSize: 20),
                ),
                onTap: (){
                  Navigator.of(context).push(MaterialPageRoute(builder: (context)=> Secondpage()));
                },
              ),

            ],
          ),
        ),
      ),
```


