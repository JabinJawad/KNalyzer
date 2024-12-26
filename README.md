# **K'Nalyzer - Domain Analyzer**

### **Overview**
K'Nalyzer is a powerful and easy-to-use tool designed to analyze and gather detailed information about domains and IP addresses. Whether you're a cybersecurity professional, a network administrator, or a casual user, K'Nalyzer helps you understand the technical aspects of any domain or IP, providing you with WHOIS data, DNS records, SSL certificate information, hosting provider details, and more.

### **Key Benefits**
- **Comprehensive Domain Analysis**: K'Nalyzer provides a complete breakdown of domain data, including WHOIS information, DNS records, IP geolocation, hosting details, SSL certificate status, and much more.
- **Subdomain Detection**: Identify subdomains related to a domain and gather useful insights on their status and configuration.
- **Report Generation**: Generate a detailed PDF report containing all analysis results for later reference.
- **User-Friendly Interface**: With its interactive console interface, K'Nalyzer is designed to be simple and intuitive for both beginners and experienced users.
- **Security Insights**: Get valuable recommendations to improve the security and performance of your domain, such as enabling DNSSEC, using a CDN, and more.

---

### **Features**
- **Comprehensive Analysis**: Perform in-depth analysis using K'Nalyzer's advanced algorithms for WHOIS data, DNS, IP information, and more.
- **Subdomain Discovery**: Automatically detect and list subdomains associated with a domain.
- **SSL Certificate Inspection**: Examine SSL certificates to ensure they are valid and secure.
- **Technology Stack Detection**: Identify technologies like web servers, hosting providers, and CDNs used by the domain.
- **PDF Report Generation**: Easily generate a downloadable PDF report containing all analysis results.
- **Recommendations**: Get suggestions to improve domain security and performance.

---
### **Getting Started**
#### **Download the Tool**
1. Go to the [Releases Section](https://github.com/JabinJawad/KNalyzer/releases) to download the latest version of K'Nalyzer.
2. Click on the `.exe` file to download.

#### **Run the Tool**
1. Double-click on the downloaded `.exe` file.
2. Follow the on-screen instructions to start using K'Nalyzer.

> **Note**: If you encounter a warning about "Unknown Publisher," it's safe to proceed as the file is hosted on GitHub for secure distribution.

---

### **FAQs**
#### **1. Why does my antivirus flag this tool?**
Some antivirus software might flag the file as suspicious because it’s an unsigned executable. Rest assured, the file is safe if downloaded directly from this repository.

#### **2. Does the tool require an internet connection?**
Yes.

---

### **Support**
- **Issues**: Found a bug or have a feature request? Submit an issue in the [Issues Section](https://github.com/JabinJawad/KNalyzer/issues).
- **Tips**: Like the tool? Support the developer by [buying a coffee](https://buymeacoffee.com/jabinjawad).

---

### **License**
This tool is distributed as **Freeware** for non-commercial use. Contact the author for commercial licensing options.

---

### **Sample Output**

Here’s an example of what the output from K'Nalyzer looks like when analyzing a domain:

```plaintext
Enter the domain to analyze: alicornmed.com

Analyzing domain: alicornmed.com

Fetching WHOIS data...
Fetching DNS records...
Fetching IPInfo data...
Inspecting SSL certificate...
Identifying CDN provider...
Detecting Email provider...
Identifying Hosting provider...
Detecting technologies...
Detecting subdomains...

+════════════════════════════════════════════════════════════════════════════════════════════+
║                                                                                   ver: 4.3 ║
║                                         K'Nalyzer                                          ║
║                                                                                     by: JJ ║
+════════════════════════════════════════════════════════════════════════════════════════════+
+-------------------+------------------------------------------------------------------------+
| Domain            | alicornmed.com
+-------------------+------------------------------------------------------------------------+
| Registrar         | Domainshype.com, Inc
+-------------------+------------------------------------------------------------------------+
| WHOIS Server      | whois.domainshype.com
+-------------------+------------------------------------------------------------------------+
| Hosting Provider  | HostGator
+-------------------+------------------------------------------------------------------------+
| SSL Provider      | Let's Encrypt
+-------------------+------------------------------------------------------------------------+
| CDN Provider      | Unknown CDN Provider
+-------------------+------------------------------------------------------------------------+
| IP Information    | IP Address: 103.50.160.145
|                   | Company: AS394695 PDR
|                   | Hostname: cp-in-16.webhostbox.net
|                   | Location: Mumbai, Maharashtra, IN
+-------------------+------------------------------------------------------------------------+
| Technologies Used | Webserver: Apache
|                   | Technology: Unknown
+-------------------+------------------------------------------------------------------------+
| Subdomains Count  | 13
+-------------------+------------------------------------------------------------------------+
| Subdomain Names   |
|                   | cpanel.alicornmed.com ---> 103.50.160.145
|                   | www.alicornmed.com ---> 103.50.160.145
|                   | mail.alicornmed.com ---> 103.50.160.145
|                   | autodiscover.alicornmed.com ---> IP Not Found
|                   | webmail.alicornmed.com ---> 103.50.160.145
|                   | *.alicornmed.com ---> IP Not Found
|                   | cpcontacts.alicornmed.com ---> 103.50.160.145
|                   | cpcalendars.alicornmed.com ---> 103.50.160.145
|                   | alicornmed.com ---> 103.50.160.145
|                   | www.alicornmed.com.cp-in-16.hostgatorwebservers.com ---> 103.50.160.145
|                   | mail.alicornmed.com.cp-in-16.hostgatorwebservers.com ---> 103.50.160.145
|                   | alicornmed.com.cp-in-16.hostgatorwebservers.com ---> 103.50.160.145
+-------------------+------------------------------------------------------------------------+
| A Records         | 103.50.160.145
+-------------------+------------------------------------------------------------------------+
| CNAME Records     | Not Found
+-------------------+------------------------------------------------------------------------+
| TXT Records       | "v=spf1 +a +mx include:webhostbox.net ~all"
+-------------------+------------------------------------------------------------------------+
| MX Records        | 0 alicornmed.com.
+-------------------+------------------------------------------------------------------------+
| NS Records        | ns2.cp-in-16.hostgatorwebservers.com.
|                   | ns1.cp-in-16.hostgatorwebservers.com.
+-------------------+------------------------------------------------------------------------+
| DMARC Records     | Not Found
+-------------------+------------------------------------------------------------------------+
+════════════════════════════════════════════════════════════════════════════════════════════+
║                                                                                   ver: 4.3 ║
║                                 Thanks for using K'Nalyzer                                 ║
║                                                                                     by: JJ ║
+════════════════════════════════════════════════════════════════════════════════════════════+

Recommendations:
   - Consider migrating to a Public Cloud like AWS, Google Cloud, or Azure for better scalability and reliability.
   - Consider using a CDN like Cloudflare.
   - Use a reliable email provider like Google Workspace, Microsoft 365, or AWS SES
   - Consider implementing DMARC for better email security.
   - DNSSEC is not enabled, consider enabling it for added DNS security.

What Would You Like to Do Next?
    Press "1" to Analyze Another Domain.
    Press "2" to Get the Full List of Subdomains.
    Press "3" to Generate a PDF Report.
    Press "4" to Analyze Another IP Address.
    Press "5" to Quit.

Enter your choice: 2

+---------------------- List of 13 Subdomains of alicornmed.com ----------------------+

+------------------------------------------------------+----------------+ 
| Subdomain                                            | IP Address     |
+======================================================+================+
| webdisk.alicornmed.com                               | 103.50.160.145 |
+------------------------------------------------------+----------------+
| *.alicornmed.com                                     | IP Not Found   |
+------------------------------------------------------+----------------+
| cpanel.alicornmed.com                                | 103.50.160.145 |
+------------------------------------------------------+----------------+
| cpcalendars.alicornmed.com                           | 103.50.160.145 |
+------------------------------------------------------+----------------+
| mail.alicornmed.com.cp-in-16.hostgatorwebservers.com | 103.50.160.145 |
+------------------------------------------------------+----------------+
| mail.alicornmed.com                                  | 103.50.160.145 |
+------------------------------------------------------+----------------+
| autodiscover.alicornmed.com                          | IP Not Found   |
+------------------------------------------------------+----------------+
| www.alicornmed.com                                   | 103.50.160.145 |
+------------------------------------------------------+----------------+
| cpcontacts.alicornmed.com                            | 103.50.160.145 |
+------------------------------------------------------+----------------+
| www.alicornmed.com.cp-in-16.hostgatorwebservers.com  | 103.50.160.145 |
+------------------------------------------------------+----------------+
| alicornmed.com.cp-in-16.hostgatorwebservers.com      | 103.50.160.145 |
+------------------------------------------------------+----------------+
| webmail.alicornmed.com                               | 103.50.160.145 |
+------------------------------------------------------+----------------+
| alicornmed.com                                       | 103.50.160.145 |
+------------------------------------------------------+----------------+
+-----------------------------------------------------------------------------------+

What Would You Like to Do Next?
    Press "1" to Analyze Another Domain.
    Press "2" to Get the Full List of Subdomains.
    Press "3" to Generate a PDF Report.
    Press "4" to Analyze Another IP Address.
    Press "5" to Quit.

Enter your choice: 3

PDF Report Generated Successfully! & saved as K'Nalyzer-Report_alicornmed.com.pdf

What Would You Like to Do Next?
    Press "1" to Analyze Another Domain.
    Press "2" to Get the Full List of Subdomains.
    Press "3" to Generate a PDF Report.
    Press "4" to Analyze Another IP Address.
    Press "5" to Quit.

Enter your choice: 4

Enter the IP to analyze: 104.18.40.176

                IP Address    : 104.18.40.176
                Company       : AS13335 Cloudflare, Inc.
                Hostname      : Unknown
                IP Geolocation: San Francisco
                Region        : California
                Country       : US
                Timezone      : America/Los_Angeles


What Would You Like to Do Next?
    Press "1" to Analyze Another Domain.
    Press "2" to Get the Full List of Subdomains.
    Press "3" to Generate a PDF Report.
    Press "4" to Analyze Another IP Address.
    Press "5" to Quit.

Enter your choice: 

---
