# CodeCapture

![CodeCapture-Banner](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/CodeCapture-Banner-JPG.jpg/1024px-CodeCapture-Banner-JPG.jpg)


## Description

**CodeCapture** is a Xamarin.Forms application that captures (clicks using the device Camera or selects from the device storage) a picture of hand-written/printed code (Java, C++, Python, or JavaScript), extracts the text from it using the Azure Computer Vision Read API, compiles it and returns the result using the JDoodle Compiler API, and allows the user to email the code, standard input, and result to any email address of their preference.


* Check out the [demo video](https://drive.google.com/file/d/1DcOOoLNKLJDhfVcw4a8cRhlgX1Ls16m5/view?usp=sharing)

* Download the [Android APK (for testing)](https://drive.google.com/file/d/10sGT82si_TRWNH7rk4pth5CK-Ep6YfRu/view?usp=sharing)
 

## Inspiration

While in recent times, the world has started moving towards pro-CS education, the fact is that buying computers is a distant dream for most students and educational institutions across the globe even today. In most developing countries, the ratio of CS students versus the number of computers available is highly skewed and most students are still learning programming via pen-and-paper. At the same time, however, the number of people who own mobile phones has significantly increased. Bridging this gap between pen-and-paper coding and coding on a computer by using a technology that people already own can  bring a significant difference in the adoption of Computer Science education today.


## Dependencies

The following **NuGet** packages are necessary to build and run this project:

* [Xamarin.Forms](https://www.nuget.org/packages/Xamarin.Forms/4.8.0.1364?_src=template)

* [Xamarin.Essentials](https://www.nuget.org/packages/Xamarin.Essentials/1.5.3.2?_src=template)

* [NETStandard.Library](https://www.nuget.org/packages/NETStandard.Library/2.0.3?_src=template)

* [Microsoft.NETCore.UniversalWindowsPlatform](https://www.nuget.org/packages/Microsoft.NETCore.UniversalWindowsPlatform/6.2.10?_src=template)

* [Newtonsoft.Json](https://www.nuget.org/packages/Newtonsoft.Json/12.0.3?_src=template)

* [Xam.Plugin.Media](https://www.nuget.org/packages/Xam.Plugin.Media/5.0.1?_src=template)


## Steps To Run

Please follow the following steps to run the project in **Visual Studio 2019**

1. Clone the repository to a location of your preference

2. Open the project in Visual Studio 2019 by clicking on **CodeCapture.sln**

3. Install all the dependencies mentioned above using the **NuGet Package Manager** 

4. Go to the location **../CodeCapture/CodeCapture/Models** and create a **Secrets.cs** file based on the template in the **Secrets.MD** file
   (For more information on how to create the resources for Azure Computer Vision Read API and JDoodle Compiler API, scroll below)

5. Build the project
 
6. Run and enjoy :)


## Setting Up The APIs

* In order to learn how to set up the **Azure Computer Vision** resource, please do visit the following link: [Resource Set-up Quickstart](https://docs.microsoft.com/en-us/azure/cognitive-services/cognitive-services-apis-create-account?tabs=singleservice%2Cwindows)

*Note: Since we have the **Secrets.cs** file, you will not need to create an Environment Variable separately*

If you are a full-time student, you can avail the [Azure For Students](https://aka.ms/a4s) offer and receive $100 worth of Azure credits as well as various free developer tools

* In order to set up your credentials for the **JDoodle Compiler API**, please visit the following link: [Compiler API](https://www.jdoodle.com/compiler-api/)

You can view the [JDoodle Compiler API Documentation](https://docs.jdoodle.com/compiler-api/compiler-api) to understand how the API works so that you can tweak the app for your personal work too