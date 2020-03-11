# Radio App Setup

In this section, we explain the common things you can do to a certain component/template.

In the radio app, there are two mods. 

1. Multi-radio station
2. Single radio station 

In the case of the 2, where you have a single radio station it is common that you want the app to start playing soon as user open the app. So the idea will be to directly go in that radio details page. 

And yes, this is possible but requires small manual work. 

You should already have added a radio station, you have learned that in "Section content".

![](../.gitbook/assets/image%20%2814%29.png)

Go in that that radio station, that you want to open/start when app starts.

![](../.gitbook/assets/image%20%286%29.png)

At the top, in the address bar, you will notice a radio station ID number.

![](../.gitbook/assets/image%20%282%29.png)

Copy that number. 

Now go to Setting of the radio station. 

![](../.gitbook/assets/image%20%2818%29.png)

There you will see "**ObjectIdToShow**"

Enter the copied number there.  Now your station will start directly. 

Note that this can be applied to every section. you can manually add the o**bjectIdToShow** key.

![](../.gitbook/assets/image%20%2815%29.png)

