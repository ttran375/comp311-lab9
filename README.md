# comp311-testem
# Steps

1. **Check that Node.js and npm are installed**
   ```sh
   node -v
   npm -v
   ```

2. **Create a working directory for the workshop**
   ```sh
   mkdir testem-workshop-yourname
   ```

3. **Change the current directory to the new directory**
   ```sh
   cd testem-workshop-yourname
   ```

4. **Check whether Testem is installed**
   ```sh
   testem --help
   ```

5. **Install Testem (if it is not installed)**
   ```sh
   npm install testem
   ```

6. **Execute Testem**
   ```sh
   testem-workshop-yourname\node_modules\.bin\testem
   ```

7. **Open the address provided by Testem in your browser**
   ```
   localhost:7357
   ```

8. **Create a file named `hello_spec.js` with the following content**
   ```js
   describe('hello', function() {
     it('should say hello', function() {
       expect(hello()).toBe('hello world');
     });
   });
   ```

9. **Implement `hello` in a file named `hello.js`**
   ```js
   function hello() {
     return "hello world";
   }
   ```

---

### Steps for Windows

1. **Open Command Prompt and navigate to the directory**
   ```sh
   Microsoft Windows [Version 10.0.16299.492]
   (c) 2017 Microsoft Corporation. All rights reserved.

   C:\Users\bgoel>cd testem-workshop-yourname
   ```

2. **Install Testem**
   ```sh
   C:\Users\bgoel\testem-workshop-yourname>npm install testem
   ```

3. **Execute Testem**
   ```sh
   C:\Users\bgoel\testem-workshop-yourname\node_modules\.bin\testem
   ```

4. **Open another Command Prompt to create and edit files**

   - **Create and edit `hello_spec.js`**
     ```sh
     C:\Users\bgoel\testem-workshop-yourname>notepad hello_spec.js
     ```

   - **Create and edit `hello.js`**
     ```sh
     C:\Users\bgoel\testem-workshop-yourname>notepad hello.js
     ```

---

### Submission

Make screenshots of the above steps and submit them in the `Testem_workshop` assignment folder.