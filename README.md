### 1. Make sure your Visual Studio 2019 have installed C++ package with C++/CLR:
![](https://uupload.ir/files/8svz_screenshot_2021-04-22_200543.png)
![](https://uupload.ir/files/q3is_screenshot_2021-04-22_200603.png)
![](https://uupload.ir/files/eve_screenshot_2021-04-22_200617.png)
### 2. If you have installed all the package and components, then open Visual Studio 2019 and create a new project
![](https://uupload.ir/files/1tto_screenshot_2021-04-22_200631.png)
### 3. Add a new item:
![](https://uupload.ir/files/hln7_screenshot_2021-04-22_200642.png)
![](https://uupload.ir/files/x4fo_screenshot_2021-04-22_200659.png)
![](https://uupload.ir/files/akna_screenshot_2021-04-22_200710.png)
**Don't worry, close it and add the following code to the TestForm.cpp:**

    using namespace System;
    using namespace System::Windows::Forms;
    
    [STAThreadAttribute]
    void Main(array<String^>^ args)
    {
        Application::EnableVisualStyles();
        Application::SetCompatibleTextRenderingDefault(false);
        Test::TestForm form;
        Application::Run(%form);
    }
![](https://uupload.ir/files/oz5l_screenshot_2021-04-22_200721.png)
### 4. Right click on the Project and choose Properties option:
![](https://uupload.ir/files/xz8s_screenshot_2021-04-22_200736.png)
**then :**
![](https://uupload.ir/files/8ku8_screenshot_2021-04-22_200753.png)
### 5. ![](https://uupload.ir/files/fti2_screenshot_2021-04-22_200806.png)
Then save it and close the Visual Studio 2019, then reopen your Test.
![](https://uupload.ir/files/pi5a_screenshot_2021-04-22_200818.png)
### 6. And the display:
![](https://uupload.ir/files/vdo5_screenshot_2021-04-22_200833.png)
![](https://uupload.ir/files/bkmg_screenshot_2021-04-22_200846.png)
![](https://uupload.ir/files/0no_screenshot_2021-04-22_200857.png)
![](https://uupload.ir/files/3jh9_screenshot_2021-04-22_200912.png)

**That's all, hope this helps!**
> #### Amirreza Tavakoli
