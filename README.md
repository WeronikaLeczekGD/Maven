# Maven

1. Install locally the latest versions of Java and Maven.
2. Go to https://github.com/spring-projects/spring-petclinic, fork it and clone the forked repo.
3. Perform validation to check if the project is correct.
4. [Build JAR artifact from source code, run the application locally and see the web interface in the browser.](#ad-4)

5. [Increase project version to 3.0.0 without interactive mode. Use release plugin.](#ad-5)

6. [In pom file add scm section with your repo address. Prepare code to release.](#ad-6)
7. [Try to prepare release in non-interactive mode.](#ad-7)
8. [Try to perform the release of artifacts.](#ad-8)
9. [Perform release cleanup.](#ad-9)


## Ad 4

1. Used commands:

![Screenshot 2022-11-20 at 11 31 02](https://user-images.githubusercontent.com/114099418/202907347-49391cce-1028-47fe-8e90-d6e01458ea37.png)

2. Web intefrace in the browser:

![Screenshot 2022-11-20 at 15 37 11](https://user-images.githubusercontent.com/114099418/202908355-a0f93df4-05c4-4f79-8e84-27e7ede8bacf.png)


## Ad 5

1. Here i have changed version:

![Screenshot 2022-11-20 at 15 22 40](https://user-images.githubusercontent.com/114099418/202907583-65d6f110-c887-4c49-bf13-38b8aa71236f.png)


## Ad 6

1. Adding scm section in pom.xml:

![Screenshot 2022-11-20 at 15 24 16](https://user-images.githubusercontent.com/114099418/202907702-1edd9d71-e8b4-4e65-85fc-8b7729c48314.png)

2. Preparing code to release:

*adding maven-release-plugin:

![Screenshot 2022-11-20 at 15 27 35](https://user-images.githubusercontent.com/114099418/202907872-01cea795-2a5b-4aa4-8183-1053d2e9d745.png)

## Ad 7

1. To prepare release in non-interactive mode I used this command:

![Screenshot 2022-11-20 at 15 53 34](https://user-images.githubusercontent.com/114099418/202909134-4c8b71ab-e89b-4c5f-a8db-322659ec92aa.png)


* Command above created tag in my repozitory:

![Screenshot 2022-11-20 at 15 47 31](https://user-images.githubusercontent.com/114099418/202908837-04a21629-6950-4e09-98d8-b8cf2b8e2d58.png)


## Ad 8

1. To perform the release of artifact I used command:

![Screenshot 2022-11-20 at 15 57 26](https://user-images.githubusercontent.com/114099418/202909308-452a5a23-f08f-4de9-ac1f-d5150ca07fcf.png)

* But then I got this error:

![Screenshot 2022-11-20 at 15 51 30](https://user-images.githubusercontent.com/114099418/202909022-e09a346c-803d-4579-8f34-e797e8aa41b4.png)

* I think it is because I need to have a server to perform the release of arfifact to. Url should be added here instead of my git repozitory url:

![Screenshot 2022-11-20 at 16 01 09](https://user-images.githubusercontent.com/114099418/202909494-b3ce5bb2-d5a1-4f8c-996e-5a88724f8682.png)


## Ad 9

1. To perform release cleanup I used command belove.

![Screenshot 2022-11-20 at 16 02 01](https://user-images.githubusercontent.com/114099418/202909532-fe8c97ea-8d38-4000-b988-aceaa04c5e76.png)

Thanks to this my local repozitory ....
