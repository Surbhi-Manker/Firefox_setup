# Firefox_setup


package packone;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.firefox.FirefoxDriver;

public class test_one {

public static void main(String[] args) {
	
   System.out.println("Hello Surbhi");
		 
   System.setProperty("webdriver.chrome.driver","C:\\Users\\lenovo\\Downloads\\Surbhi\\SELENIUM\\chromedriver_win32\\chromedriver.exe");
   WebDriver driver=new ChromeDriver();
   
   driver.get("https://www.google.com/");

   System.setProperty("webdriver.gecko.driver","C:\\Users\\lenovo\\Downloads\\Surbhi\\SELENIUM\\geckodriver-v0.29.0-win64\\geckodriver.exe");	 
   WebDriver driver = new FirefoxDriver();

	}
}
