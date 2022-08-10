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

#
# sample drawer
# Code

![drawer0](https://user-images.githubusercontent.com/86792533/183133636-909f5258-e203-496d-b229-ac63bb83819f.png)

![drawe1](https://user-images.githubusercontent.com/86792533/183133680-22614710-725a-43d0-8ae6-f63c08d460bb.png)



