# MultiThreadedWebServer

## Points:

- **1:** Pulling lots of Requests  
- **2:** Pulled 6k requests from client in SingleThreaded almost smoothly.  
- **3:** Pulled 60k requests from Client in MultiThreaded almost smoothly.  
- **4:** Pulled 600k requests from client in ThreadPool almost smoothly, indicating efficiency difference.  
- **5:** Done with JMeter.

## How to run

### Steps

1. Clone the repository:

   ```bash
   https://github.com/aritrakar95/MultiThreadedWebServer

2. **Set up JMeter**

3. **Inside JMeter**

- Create a test run  
- Create a thread group  
- Inside it create a TCP Sampler  
- Select view results in Table, Tree, Graph  

4. **Finally run steps**

- Open terminal and select the server you want to run  
- After server port is listening, start the file in JMeter  
- Results will be displayed in JMeter  
