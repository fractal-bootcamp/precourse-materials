# NETWORKING

## QUESTIONS

- What is an IP Address? What does IP stand for?
  - An IP address is a unique name for each and every computer. The address allows any other computer know how to reach out to and make a request from that computer. I believe IP stands for Internet Protocol.
  - update: An IP address, standing for Internet Protocol address, is a numerical label assigned to every device connected to a computer network that uses the Internet Protocol for communication. Its primary function is to identify the host or network interface and provide the location for transferring data. As networks can be private or public, IP addresses can be dynamic (changing with each connection) or static (permanent for a device). An example of an IP address is 192.0.2.1
  ```bash
    # Use nslookup to find the IP address of a domain
    nslookup wikipedia.org
  ```


- What does HTTP stand for? What is the difference between HTTP and HTTPS?
  - HyperText Transfer Protocol. the S in HTTPS stands for Secure. The way the HTTPS is secured is through encryption using TLS or Transport Layer Security for formerly SSL Secure Sockets Layer. So it is referred to HTTP over SSL or HTTP over TLS.
  - update: HTTP stands for HyperText Transfer Protocol, which is the foundation of data communication on the World Wide Web. HTTPS, or HTTP Secure, incorporates encryption via TLS (Transport Layer Security) or formerly SSL (Secure Sockets Layer) to enhance security. HTTPS encrypts the data exchanged, thus protecting the integrity and confidentiality of data between the user's computer and the site, which is crucial for sensitive transactions.
  ```bash
    # Scan common HTTP and HTTPS ports to see if they are open and show service versions
    sudo nmap -p 80,443 -sV example.com
  ```


- What is a URL? What is DNS?
  - Uniform Resource Locator is the human readable domain name of a website that we type into a URL bar like www.wikipedia.org, when we hit enter the request is routed through a Domain Name System or DNS to find and lookup it's IP or Internet Protocol address. Which then reroutes the request from the client's browser through the DNS lookup to the controller server that the client requested data from. DNS has been around since 1985. There are common types of records stored in the DNS, start of authority SOA, A and AAAA for IP addresses, SMTP mail exchangers MX records, name servers NS, pointers for reverse DNS lookups PTR, and domain name aliases CNAME.
  - update: A URL (Uniform Resource Locator) is the address used to access websites on the internet, specifying the location of a resource on a network. It is human-readable, such as 'www.wikipedia.org'. DNS (Domain Name System) is a system that translates these human-readable domain names into machine-readable IP addresses, facilitating the routing of requests over the internet. DNS is essentially the phonebook of the internet, containing various records like A (IPv4 address), AAAA (IPv6 address), MX (mail exchange), and CNAME (canonical name for aliases).
  - to find a trace of a request to a URL we can see how this works with the following command:
  ```bash
    sudo nmap -sn --traceroute -v wikipedia.org

    # Use dig to get detailed DNS information, including A, AAAA, and MX records
    dig wikipedia.org ANY +noall +answer

    # Use nmap to check the SSL/TLS configuration of a HTTPS server
    sudo nmap --script ssl-cert,ssl-enum-ciphers -p 443 wikipedia.org


  ```



## RESOURCES

- https://en.wikipedia.org/wiki/IP_address (https://en.wikipedia.org/wiki/IP_address)
