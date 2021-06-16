package co.task.testing;

//importing required packages


import org.openqa.selenium.By;


import org.openqa.selenium.chrome.ChromeDriver;

public class task {

	public static void main(String[] args ) throws InterruptedException {
		System.setProperty("webdriver.chrome.driver","E:\\chromedriver\\chromedriver_win32\\chromedriver.exe");
		ChromeDriver driver=new ChromeDriver();
		String url="https://www.thesparksfoundationsingapore.org/";
		//maximizes the window
		driver.manage().window().maximize();
		driver.get(url);
		//finding element
		Thread.sleep(2000);
		driver.findElement(By.linkText("Contact Us")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("GRIP (Internship)")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Why Join Us")).click();
		Thread.sleep(2000);
		driver.findElement(By.name("Name")).sendKeys("Dhanavidhyaa");
		Thread.sleep(2000);
		driver.findElement(By.name("Email")).sendKeys("dhanavidhyaa.22ee@licet.ac.in");
		Thread.sleep(2000);
		driver.findElement(By.linkText("Brand Ambassador")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Expert Mentor")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Events Volunteer")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Management Volunteer")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Programs")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Student Scholarship Program")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Student Mentorship Program")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Student SOS Program")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Student Externships Program")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Corporate Programs")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Policies and Code")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Policies")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Code of Ethics and Conduct")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Personal Data Policy")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Whistle Blowing Policy")).click();
		Thread.sleep(2000);
		driver.findElement(By.linkText("Service Quality Values")).click();
		System.out.println("Test is successful");
		driver.close();
		driver.quit();
	}

}
