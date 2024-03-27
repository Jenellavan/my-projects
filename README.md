 CREATE  A RESUME WEBSITE FROM  THE STATIC WEBSITE  USING THE AMAZOn S3 BUCKET 

To create a resume from a static website hosted on Amazon Web Services (AWS), you can follow these general steps:

1- Design the Website: First, design your resume website. You can use HTML, CSS, and JavaScript to create a static website. Ensure that the design is clean,
professional, and easy to navigate.

2-Choose AWS Services: amazon simple storage (S3) 

3-Host Website on Amazon S3:

-Sign in to the AWS Management Console and open the Amazon S3 console.

-Create an S3 bucket and upload your website files to the bucket.

![image](https://github.com/Jenellavan/my-projects/assets/149893663/2a5a85f6-4444-454f-afb2-c38adced254c)

-Make sure to enable public access to your S3 bucket and configure it for static website hosting.

![image](https://github.com/Jenellavan/my-projects/assets/149893663/8622b679-69c4-41f8-8964-3baf1d6e8dad)

4-Domain Setup (Optional): this not include in the free tier 

-If you have a domain name, you can configure it to point to your S3 bucket using Amazon Route 53 or another domain registrar.

-If you don't have a domain name, you can use the default S3 bucket URL for your resume website(exactly what i used) 

![image](https://github.com/Jenellavan/my-projects/assets/149893663/26028aa0-e54f-41d3-930a-6a30b1efbaf9)

5-Test Your Website: Verify that your website is accessible via the URL provided by Amazon S3. 

  Test all links and ensure that your resume content displays correctly.
  
![image](https://github.com/Jenellavan/my-projects/assets/149893663/08e4bbee-d6b7-4f00-a3d1-ac2699d80b48)


  
