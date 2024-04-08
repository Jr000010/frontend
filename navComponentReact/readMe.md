## React Navigation Menu
This is a react component that generates a navigation menu. The function loops over *menuItems* array items and generates the links within the resulting navigation menu.

```
**const** Navbar = () => {
    const menuItems = ['Home','About','Services','Contacts','FAQs','Blog'];
    
    return (
        <nav className="navBasic">
          <ul>
              {menuItems.map((item, index) => (
                  <a  key={index} href="#"><li>{item}</li></a>
              ))}
          </ul>
        </nav>
    );
}

export default Navbar;
```
