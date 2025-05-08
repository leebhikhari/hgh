# hgh
package pages;

import enums.UserEnum;
import interfaces.ISelector;
import org.openqa.selenium.By;
import utils.CommonUtils;

import static org.testng.Assert.assertTrue;

public class LoginPage extends CommonUtils{

    private static final String baseURL = "https://the-internet.herokuapp.com";
    private static final String login = "/login";
    private static final String pageTitle = "LOGIN_PAGE: ";

    public void navigateToLoginPage(){
        System.out.println(pageTitle + "Navigating to the Login page...");
        navigateToURL(baseURL + login);
    }
    
