## React Navigation Menu

`
const Navbar = () => {
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
`
