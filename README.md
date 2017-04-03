class users 
{
private String username;
private String password;
private String[][] accounts = {{"bindhu", "1696"},{"vijaya", "1696"}};

public static Void users(String user, String pass)
{
    username = user;
    password = pass;
}

public boolean auth(){
    if((username.equals(accounts[0][0])) && (password.equals(accounts[0][1])))
        return true;
    else
        return false;
}

}
