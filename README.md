
# Angular Interview Questions

A complete guideline to prepare for angular interviews. Also, you can use these questions to verify your expertise in angular. 



## Table of Contents
* [Assess Your Skill Level](#assess-your-skill-level)
* [Know the Interviewer](#know-the-interviewer)
* [Novice Level Questions](#novice-level)
    * [Familiarity to Basic Terminology](#familiarity-to-basic-terminology)
    * [Ability to Build Simple App](#ability-to-build-simple-app-questions)
    * [Understanding Basic Concepts](#understanding-basic-concepts-questions)
* [Intermediate Level Questions](#intermediate-level)
    * [Essential Terminology](#essential-terminology-questions)
    * [Comfortability to Build Medium Size App](#comfortability-to-build-medium-size-app-questions)
    * [Core Concepts Understandability](#core-concepts-understandability-questions)
* [Expert Level Questions](#expert-level)
    * [Performance and Edge Case Related Terminology](#performance-and-edge-case-related-terminology)
    * [Master a Large App](#master-a-large-app)
    * [Rock star and Fighter for angular](#rockstar-and-fighter-for-angular-questions)
* [Coding Test Question](#coding-test)
    * [Fetch Data and Display User Profile](#fetch-data-and-display-user-profile)
    * [Persistent Todo List](#persistent-todo-list)
    * [Student Registration System](#student-registration-system)
* [Side Things Related Questions](#side-things-related-questions)
    * [rxjs](#rxjs)
    * [TypeScript](#typescript)
    * [angular-cli](#angular-cli)
    * [others](#others)
* [Note from God](#note-from-god)



## Assess Your Skill Level
The most important step is knowing how you compare to other job seekers. Pinpoint areas where you are weaker, and spend the time necessary to make improvements. Google is your friend.

* **Novice** - You can create an Angular app using angular-cli or other popular project seeds, you have a basic understanding of components, modules, pipes, services, etc. If you don't have a clue what I am talking about, watch this [video](https://www.youtube.com/watch?v=rOr1r1rSZQ8) and get up to speed.
* **Intermediate** - You have a fully functional app that is deployed somewhere and/or published code in github, and you are comfortable with routing, authorization, feature modules, architecture, style guide, etc.
* **Expert** - You have mastered lazy loading, AOT, custom directives, deployment configuration, extending core features, etc.
* **Everyone Else** - You are either angular blind or an angular rock star. 


## Know the Interviewer
Do yourself a favor—Google the interviewer. Look at his/her Linkedin profile. Check his/her youtube videos, crappy old blog that hasn't been updated in years, and github profile. After your research, try to put the interviewer in one of the following categories:
1. Lazy interviewers wil ask about terminology. Sometimes they just Google and ask questions from there. If your interviewer is older and out of touch with the current development landscape, there is a greater chance that he/she will ask questions related to terminology.
2. More modest and nicer interviewers will be interested in what you know and whether you can get the job done. For this kind of interviewer look at the How category questions (I'm unsure what you are trying to say here)
3. Experienced interviewers (those who have been senior developers for a long time and have recently updated blogs and videos) want to know that you can think critically, and he will be interested in your process for decision making. These interviewers love to prove you wrong. One important tip: don't try to prove them wrong.

Researching relevant team members on LinkedIn and github can be useful as well.

## Novice Level

At this level an interviewer wants to know whether the interviewee is a coachable self-learner. Hence, he/she might ask questions about basic terminology, your ability to build a simple app, and your comprehension of basic concepts.  


### Familiarity of Basic Terminology
1. What are the differences between AngularJS (angular 1.x) and Angular (Angular 2.x and beyond)?
2. What is a component? Why would you use it? 
3. What is the minimum definition of a component?
4. What is a module, and what does it contain?
5. What is a service, and when will you use it?
6. What is a promise? Explain it laymen's terms.
7. What are the lifecycle hooks for components and directives?
8. What are pipes? Give me an example.
9. What are the differences between reactive forms and template driven forms?
10. What is a dumb, or presentation, component? What are the benefits of using dumb components?



### Ability to Build Simple App
1. How do components communicate with each other?
2. How would you use http to load data from server? 
3. How do you create routes?
4. How can you get the current state of a route?
5. How do you create two-way data binding?
6. How do you load external modules?
7. How would you display form validation errors?
8. Which lifecycle hook would you use to unsubscribe an observable?
9. How are services injected to your application?
10. How would you create route parameters and access them from a component?



### Basic Concepts
1. Why would you use Angular instead of another framework, e.g., React?
2. What is the difference between an observable and a promise?
3. What is the difference between a component and a directive?
4. Why would you use typescript aka benefits of typescript?
5. Why different life cycle hooks are needed for a component/directive?
6. Why does angular use rxjs?
7. What is the purpose of using zone.js?
8. What is the difference between ngOnInit() and the constructor() of a component?
9. When will ngOnInit() be called? How would you make use of ngOnInit()?
10. What are the benefits of using formBuilder?




[Answers link coming soon ]


## Intermediate Level

To be in the intermediate level, you have to build at least one medium sized angular app. You have to have familiarity with routing, https, different built process, unit test, etc. here are the questions you could expect.



### Essential Terminology Questions
1. How will you protect a route for authorized user only?
2. What is a custom pipe and how will you use it?
3. What is a structural directive?
4. What is the difference between RouterModule.forRoot() vs RouterModule.forChild()? Why is it important?
5. What is the difference between a module's forRoot() and forChild() methods and why do you need it?
6. What's the difference between dirty, touched, and pristine on a form element?
7. What is an async pipe? What kind of data can be used with async pipe?
8. What is injectable? Give me some example.
9. What is a pure pipe?
10. How will you create two-way data binding in Angular?



### Comfortability to Build Medium Size App Questions
1. How do components communicate with each other?
2. How do you decide to create a new NgModule?
3. How will you inject custom header in your http call?
4. How do you identify a structural directive in html?
5. How would you select a custom component to style it?
6. How would you select all the child components' elements?
7. How would you cache an observable data?
8. How would you save data from a form control?
9. How Event Emitters works in Angular?
10. How do you mock a service to inject in a unit test?



### Core Concepts Understandability Questions
1. Tell me about feature module and shared module?
2. What would you not put in a shared module?
3. Why angular uses decorator?
4. What is async validation and how is it done?
5. Why do you need type definitions?
6. Which components will be notified when an event is emitted?
7. Why would you export from ngModule?
8. Why is it bad if SharedModule provides a service to a lazy loaded module?
9. Can you explain the difference between ActivatedRoute and RouterState?
10. Which service will you put in the module and why?



[Answers link coming soon]



## Expert Level

You are a Rockstar in angular. You can teach other. You can lead a team of angular developers.

### Performance and Edge case Related Terminology
1. What is a factory Component?
2. What is lazy loading and why will you use it?
3. What is Ahead of time (AOT) compilation and why will you use it?
4. What are some of the Angular Style Guide suggestions you follow on your code? Why?
5. What is wildcard state?
6. How do you put animation between two states?
7. What would be a good use for NgZone service?
8. How would you protect a component being activated through the router?
9. How would you insert an embedded view from a prepared TemplateRef?
10. What is attribute directive and why will you use it?

### Master a Large App
1. How will you intercept http to inject header to each http call?
2. How would you create a component to display error messages throughout your application?
3. How will you parallelize multiple observable call?
4. How will you put one async call before another?
5. How can you use web worker in angular app?
6. What tools would you use to find a performance issue in your code?
7. What are some ways you may improve your website's scrolling performance?
8. Explain the difference between layout, painting and compositing.
9. How can you cancel a router navigation?
10. How would you animate routing?
11. How would you cancel a promise on which you are waiting?


### Rockstar and Fighter for Angular Questions
1. When does a lazy loaded module is loaded?
2. Why angular uses url segment?
3. How will you make angular app secure?
4. How will you localize numbers currencies and dates?
5. What is the best way to use translation in your app?
6. How will you setup different environment build differently for your app?
7. How will you use scss or css preprocessing with your application?
8. How will you optimize image/svg in your angular app?
9. How would you make sure an api call that needs to be called only once but with multiple conditions? Example: if you need to get some data in multiple routes but, once you get it, you can reuse it in the routes that needs it, therefor no need to make another call to your backend apis.
10. If you need to respond to two different Observable/Subject with one callback function, how would you do it? (ex: if you need to change the url through route parameters and with prev/next buttons).



## Coding Test
Sometimes interviewer gives real coding test. Most of us suck on those and feel ashamed of ourselves and then continue to work in the current job. I don't want you to saty in that miserable job. Hence, take the following coding challenges and master them. 

### Fetch Data and Display User Profile

This test has three level
1. Level 1: I am giving you an api https://api.github.com/search/users?q=eric This api takes a query parameter name "q" and passes query string to server. Server returns bunch of users. Now I want you to create a input text box and button so that you can type anything on the text box and hit on the button to retrieve data from the given api. Upon retrieval display total_count and first 10 users in the search result. Detail instruction about this test is available [here](https://github.com/khan4019/github-profile-search)
2. Level 2: Convert each user profile as a router link so that upon clicking on each user profile you will navigate to a route that has "login" property in the route. Pass user.login as route parameter. Create a separate component where you will read the route parameter and then fetch data for that user  by using this api https://api.github.com/users/eric . Please Notice that last part of this api is the user.login (the route parameter that you have passed). Finally display user image and few other information in the component
3. Level 3: use any charting framework that you can find and then create a simple bar chart to display number of followers of first 10 users


This coding test will judge your ability to use services, component, routing, data visualization, external module, observables, etc.

[Sample code link coming soon] 

### Persistent Todo List
This test has three levels
1. Level 1:  Implement a simple todo list where you can add items, mark as done
2. Level 2: Now create few categories of todo list and make it persistence in the browser
3. Level 3: Now use firebase (serverless database) to make todo list persistence across multiple devices

This coding test will judge whether you can pass data and events between components. Also, whether you are leveraging directives and understand difference between component and directives.


[Sample code link coming soon]

### Student Registration System
This test has three levels
1. Level-1: Design a system where students can login to register different courses 
2. Level-2: Add a feature so that faculties on each course can view how many students registered on the courses
3. Level-3: (I need a shower. will add text here after I clean up myself) 

This coding test will judge your understanding of architecture for a large application. Your ability to think and implement module, lazy loading, asset management etc.

[Sample code link coming soon]

## Side Things Related Questions

### rxjs
3. Why unsubscribing is important?
1. What is the difference between map and flatmap?
2. Whare are the different ways you can create an Observable?
4. What is forkJoin, zip, share?
5. Difference between hot and cold observables.

### TypeScript
1. How would you debug a typescript file?
2. How do you implement interface in typescript?
3. How would you call base class constructor from child class in typescript?
4. What is typescript language service?
5. How to declare a custom type?
6. what are some disadvantages of typescirpt? answers [here](https://www.codeproject.com/Articles/1071285/Latest-TypeScript-Interview-Questions-for-Beginner) 

### angular-cli
1. Why would you use angular cli?
2. How would you run unit test? 
3. How do you create application to use scss?
4. How to inject base href?
5. How would you extract webpack config from angular cli project?


### Others
1. What is the use of codelyzer?
2. Will you use Angular Material2?
4. How would you set different config in different deployment server?
5. What do you know about ES6?
6. What is ngUpgrage? Do you know how you can run angularJS and angular side by side?

## Q1: What is Routing Guard in Angular? ⭐

**Answer:**

Angular’s route guards are interfaces which can tell the router whether or not it should allow navigation to a requested route. They make this decision by looking for a true or false return value from a class which implements the given guard interface.

🔗 **Source:** [medium.com](https://medium.com/@ryanchenkie_40935/angular-authentication-using-route-guards-bf7a4ca13ae3)


## Q2: What is a module, and what does it contain? ⭐

**Answer:**

An Angular module is set of Angular basic building blocks like component, directives, services etc. An app can have more than one module.

A module can be created using `@NgModule` decorator.

```js
@NgModule({
  imports:      [ BrowserModule ],
  declarations: [ AppComponent ],
  bootstrap:    [ AppComponent ]
})
export class AppModule { }
```

🔗 **Source:** [stackoverflow.com](https://stackoverflow.com/questions/40073941/whats-the-difference-between-an-angular-component-and-module)


## Q3: What are pipes? Give me an example. ⭐

**Answer:**

A **pipe** takes in data as input and transforms it to a desired output. You can chain pipes together in potentially useful combinations. You can write your own custom pipes. Angular comes with a stock of pipes such as `DatePipe`, `UpperCasePipe`, `LowerCasePipe`, `CurrencyPipe`, and `PercentPipe`.

Consider:
```html
<p>The hero's birthday is {{ birthday | date }}</p>
```
In this page, you'll use pipes to transform a component's birthday property into a human-friendly date.

🔗 **Source:** [angular.io](https://angular.io/guide/pipes)


## Q4: What are the differences between AngularJS (angular 1.x) and Angular (Angular 2.x and beyond)? ⭐⭐

**Answer:**

Angular and AngularJS is basically a different framework with the same name.

Angular is more ready for the current state of web standards and the future state of the web (ES6\7, immutiablity, components, shadow DOM, service workers, mobile compatibilty, modules, typescript and so on and so on... )

Angular killed many main features in AngularJS like - controllers, $scope, directives (replaced with `@component` annotations), the module definition, and much more, even simple things like ng-repeat has not left the same as it was.

Also: 
1. They added an angular `cli`.
2. Your angular code is written in ES6 Typescript and it compiles at runtime to Javascript in the browser.
3. You bind to your HTML similarly like how you would if in an Angular 1 directive. So variable like $scope and $rootScope have been deprecated.

🔗 **Source:** [stackoverflow.com](https://stackoverflow.com/questions/34114593/angular-vs-angular-2)


## Q5: What is a component? Why would you use it? ⭐⭐

**Answer:**

*Components* are the most basic building block of an UI in an Angular application. An Angular application is a tree of Angular components. Angular components are a subset of directives. Unlike directives, components always have a template and only one component can be instantiated per an element in a template.

A component must belong to an NgModule in order for it to be usable by another component or application. To specify that a component is a member of an NgModule, you should list it in the `declarations` field of that NgModule.

```js
@Component({selector: 'greet', template: 'Hello {{name}}!'})
class Greet {
  name: string = 'World';
}
```

🔗 **Source:** [angular.io](https://angular.io/api/core/Component)


## Q6: What is the minimum definition of a component? ⭐⭐

**Answer:**

The absolute minimal configuration for a `@Component` in Angular is a template. Both template properties are set to optional because you have to define either `template` or `templateUrl`.

When you don't define them, you will get an exception like this:
```sh
No template specified for component 'ComponentName'
```
A selector property is not required, as you can also use your components in a route.

🔗 **Source:** [stackoverflow.com](https://stackoverflow.com/questions/46338698/minimum-definition-of-a-component-angular-4)


## Q7: What's the difference between an Angular component and module? ⭐⭐

**Answer:**

*Components* control views (html). They also communicate with other components and services to bring functionality to your app.

*Modules* consist of one or more components. They do not control any html. Your modules declare which components can be used by components belonging to other modules, which classes will be injected by the dependency injector and which component gets bootstrapped. Modules allow you to manage your components to bring modularity to your app.

🔗 **Source:** [stackoverflow.com](https://stackoverflow.com/questions/40073941/whats-the-difference-between-an-angular-component-and-module)


## Q8: What is a service, and when will you use it? ⭐⭐

**Answer:**

*Angular services* are singleton objects which get instantiated only once during the lifetime of an application. They contain methods that maintain data throughout the life of an application, i.e. data does not get refreshed and is available all the time. The main objective of a service is to organize and share business logic, models, or data and functions with different components of an Angular application.

The *separation of concerns* is the main reason why Angular services came into existence. An Angular service is a stateless object and provides some very useful functions. 

🔗 **Source:** [dzone.com](https://dzone.com/articles/what-is-a-service-in-angular-js-why-to-use-it)


## Q9: What is the equivalent of ngShow and ngHide in Angular? ⭐⭐

**Answer:**

Just bind to the `hidden` property

🔗 **Source:** [stackoverflow.com](https://stackoverflow.com/questions/35578083)


## Q10: You have an HTML response I want to display. How do I do that?  ⭐⭐

**Answer:**

The correct syntax is the following:
```html
<div [innerHTML]="theHtmlString"></div>
```
Working in `5.2.6`

🔗 **Source:** [medium.com](https://medium.com/wizardnet972/48-answers-on-stack-overflow-to-the-most-popular-angular-questions-52f9eb430ab0)


## Q11: How can I select an element in a component template? ⭐⭐

**Answer:**

You can get a handle to the DOM element via ElementRef by injecting it into your component's constructor:

```js
constructor(myElement: ElementRef) { ... }
```

🔗 **Source:** [medium.com](https://medium.com/wizardnet972/48-answers-on-stack-overflow-to-the-most-popular-angular-questions-52f9eb430ab0)


## Q12: What is the equivalent of "ngShow" and "ngHide" in Angular? ⭐⭐

**Answer:**

Just bind to the hidden property:

```js
[hidden]="!myVar"
```

🔗 **Source:** [medium.com](https://medium.com/wizardnet972/48-answers-on-stack-overflow-to-the-most-popular-angular-questions-52f9eb430ab0)


## Q13: What is the difference between *ngIf vs [hidden]? ⭐⭐

**Answer:**

`*ngIf` effectively removes its content from the DOM while `[hidden]` modifies the `display` property and only instructs the browser to not show the content but the DOM still contains it.

🔗 **Source:** [medium.com](https://medium.com/wizardnet972/48-answers-on-stack-overflow-to-the-most-popular-angular-questions-52f9eb430ab0)


## Q14: What is the difference between "@Component" and "@Directive" in Angular?  ⭐⭐

**Answer:**

* **Directives** add behaviour to an existing DOM element or an existing component instance.
* **A component**, rather than adding/modifying behaviour, actually creates its own view (hierarchy of DOM elements) with attached behaviour.

Write a component when you want to create a reusable set of DOM elements of UI with custom behaviour. Write a directive when you want to write reusable behaviour to supplement existing DOM elements.

🔗 **Source:** [medium.com](https://medium.com/wizardnet972/48-answers-on-stack-overflow-to-the-most-popular-angular-questions-52f9eb430ab0)


## Q15: What does this line do? ⭐⭐

**Questions Details:**

```js
@HostBinding('[class.valid]') isValid;
```


**Answer:**

`@HostBinding` lets you set properties on the element or component that hosts the directive.

The code applies the css class `valid` to whatever is using this directive conditionally based on the value of isValid.

🔗 **Source:** [alligator.io](https://alligator.io/angular/hostbinding-hostlistener/)


## Q16: How would you protect a component being activated through the router? ⭐⭐

**Answer:**

The Angular router ships with a feature called guards. These provide us with ways to control the flow of our application. We can stop a user from visitng certain routes, stop a user from leaving routes, and more. The overall process for protecting Angular routes:

* Create a guard service: `ng g guard auth`
* Create `canActivate()` or `canActivateChild()` methods
* Use the guard when defining routes

```js
// import the newly created AuthGuard
const routes: Routes = [
  {
    path: 'account',
    canActivate: [AuthGuard]
  }
];
```

Some other available guards:

* `CanActivate`: Check if a user has access
* `CanActivateChild`: Check if a user has access to any of the child routes
* `CanDeactivate`: Can a user leave a page? For example, they haven't finished editing a post
* `Resolve`: Grab data before the route is instantiated
* `CanLoad`: Check to see if we can load the routes assets

🔗 **Source:** [scotch.io](https://scotch.io/tutorials/protecting-angular-v2-routes-with-canactivatecanactivatechild-guards)


## Q17: What are some differences between Angular 2 and 4? ⭐⭐

**Answer:**

Just to name a few:
* Improvements in AOT, 
* allowing the "else" clause in ngIf, 
* support for TypeScript 2.1
* breaking out the animations package

🔗 **Source:** [github.com/WebPredict](https://github.com/WebPredict/angular-2-interview-questions)


## Q18: How would you run unit test? ⭐⭐

**Answer:**

The Angular CLI downloads and install everything you need to test an Angular application with the Jasmine test framework.

The project you create with the CLI is immediately ready to test. Just run this one CLI command:

```sh
ng test
```

🔗 **Source:** [angular.io](https://angular.io/guide/testing)


## Q19: What is the difference between Structural and Attribute directives in Angular? ⭐⭐

**Answer:**

* **Structural directives** are used to alter the DOM layout by removing and adding DOM elements. It is far better in changing the structure of the view. Examples of Structural directives are NgFor and Nglf.

* **Attribute Directives** These are being used as characteristics of elements. For example, a directive such as built-in NgStyle in the template Syntax guide is an attribute directive.

🔗 **Source:** [onlineinterviewquestions.com](https://www.onlineinterviewquestions.com/angular-7-interview-questions/)


## Q20: What is the purpose of base href tag? ⭐⭐

**Answer:**

The routing application should add <base> element to the index.html as the first child in the <head> tag inorder to indicate how to compose navigation URLs. If app folder is the application root then you can set the href value as below
```html
    <base href="/">
```

🔗 **Source:** [github.com/sudheerj](https://github.com/sudheerj/angular-interview-questions/blob/master/README.md)


## Q21: What is an observer? ⭐⭐

**Answer:**

Observer is an interface for a consumer of push-based notifications delivered by an Observable. It has below structure,
```javascript
    interface Observer<T> {
      closed?: boolean;
      next: (value: T) => void;
      error: (err: any) => void;
      complete: () => void;
    }
```
A handler that implements the Observer interface for receiving observable notifications will be passed as a parameter for observable as below,
```javascript
    myObservable.subscribe(myObserver);
```
**Note:** If you don't supply a handler for a notification type, the observer ignores notifications of that type.

🔗 **Source:** [github.com/sudheerj](https://github.com/sudheerj/angular-interview-questions/blob/master/README.md)


## Q22: What is an observable? ⭐⭐

**Answer:**

 An Observable is a unique Object similar to a Promise that can help manage async code. Observables are not part of the JavaScript language so we need to rely on a popular Observable library called RxJS.
    The observables are created using new keyword. Let see the simple example of observable,
```javascript
    import { Observable } from 'rxjs';

    const observable = new Observable(observer => {
      setTimeout(() => {
        observer.next('Hello from a Observable!');
      }, 2000);
    });`
```

🔗 **Source:** [github.com/sudheerj](https://github.com/sudheerj/angular-interview-questions/blob/master/README.md)


## Q23: What are observables? ⭐⭐

**Answer:**

**Observables** are declarative which provide support for passing messages between publishers and subscribers in your application. They are mainly used for event handling, asynchronous programming, and handling multiple values. In this case, you define a function for publishing values, but it is not executed until a consumer subscribes to it. The subscribed consumer then receives notifications until the function completes, or until they unsubscribe.

🔗 **Source:** [github.com/sudheerj](https://github.com/sudheerj/angular-interview-questions/blob/master/README.md)


## Q24: What is a bootstrapping module? ⭐⭐

**Answer:**

Every application has at least one Angular module, the root module that you bootstrap to launch the application is called as bootstrapping module. It is commonly known as AppModule. The default structure of AppModule generated by AngularCLI would be as follows,
```javascript
    /* JavaScript imports */
    import { BrowserModule } from '@angular/platform-browser';
    import { NgModule } from '@angular/core';
    import { FormsModule } from '@angular/forms';
    import { HttpClientModule } from '@angular/common/http';

    import { AppComponent } from './app.component';

    /* the AppModule class with the @NgModule decorator */
    @NgModule({
      declarations: [
        AppComponent
      ],
      imports: [
        BrowserModule,
        FormsModule,
        HttpClientModule
      ],
      providers: [],
      bootstrap: [AppComponent]
    })
    export class AppModule { }
```

🔗 **Source:** [github.com/sudheerj](https://github.com/sudheerj/angular-interview-questions/blob/master/README.md)


## Q25: What is interpolation? ⭐⭐

**Answer:**

**Interpolation** is a special syntax that Angular converts into property binding. It’s a convenient alternative to property binding. It is represented by double curly braces({{}}). The text between the braces is often the name of a component property. Angular replaces that name with the string value of the corresponding component property.
Let's take an example,
```html
    <h3>
      {{title}}
      <img src="{{url}}" style="height:30px">
    </h3>
```
In the example above, Angular evaluates the title and url properties and fills in the blanks, first displaying a bold application title and then a URL.

🔗 **Source:** [github.com/sudheerj](https://github.com/sudheerj/angular-interview-questions/blob/master/README.md)


## Q26:  Explain the difference between `Promise` and `Observable` in Angular? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q27: Explain the difference between "Constructor" and "ngOnInit" ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q28: What is the difference between `@Component` and `@Directive` in Angular? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q29: Can you explain the difference between `Promise` and `Observable` in Angular? In what scenario can we use each case? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q30: Why should `ngOnInit` be used, if we already have a `constructor`? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q31: How to bundle an Angular app for production? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q32: What is difference between "declarations", "providers" and "import" in NgModule? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q33: What is Reactive Programming and how to use one with Angular? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q34: What's new in Angular 6 and why shall we upgrade to it? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q35: Why would you use a spy in a test? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q36: What is TestBed? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q37: What is Protractor? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q38: What is the point of calling "renderer.invokeElementMethod(rendererEl, methodName)"? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q39: How would you control size of an element on resize of the window in a component? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q40: What is AOT? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q41: What is Redux and how does it relate to an Angular app? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q42: What is the use of codelyzer? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q43: How to inject base href? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q44: When would you use eager module loading? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q45: What are the Core Dependencies of Angular 7? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q46: Why Incremental DOM Has Low Memory Footprint? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q47: What are the ways to control AOT compilation? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q48: What is Angular Universal? ⭐⭐⭐

**Questions Details:**

Angular Universal is a server-side rendering module for Angular applications in various scenarios. This is a community driven project and available under`@angular/platform-server` package. Recently Angular Universal is integrated with Angular CLI.


 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q49: Do I need a Routing Module always? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q50: What is the purpose of Wildcard route? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q51: What is activated route? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q52: What is router state? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q53: What is router outlet? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q54: What are dynamic components? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q55: Explain how custom elements works internally? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q56: What are custom elements? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q57: What are the utility functions provided by RxJS? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q58: How do you perform error handling in observables? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q59: What is multicasting? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q60: What is the difference between promise and observable? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q61: What is subscribing? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q62: How do you perform Error handling for HttpClient? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q63: What is a parameterized pipe? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q64: How do you categorize data binding types? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q65: What happens if you use script tag inside template? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q66: What is the option to choose between inline and external template file? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q67: What's new in Angular 8? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q68: Angular 8: What is Bazel? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q69: Angular 8: What is Angular Ivy? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q70: Angular 8: Explain Lazy Loading in Angular 8? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q71: What are the lifecycle hooks for components and directives? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q72: When should I store the "Subscription" instances and invoke `unsubscribe()` during the NgOnDestroy life cycle and when can I simply ignore them? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q73: Could I use jQuery with Angular? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q74: How to set headers for every request in Angular? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q75: How to detect a route change in Angular? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q76: What is the need for SystemJS in Angular? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q77: Are there any pros/cons (especially performance-wise) in using local storage to replace cookie functionality? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q78: What does "detectChanges" do in Angular jasmine tests? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q79: Why would you use renderer methods instead of using native element methods? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q80: What would be a good use for NgZone service? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q81: What is Zone in Angular? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q82: How would you insert an embedded view from a prepared TemplateRef? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q83: What does a just-in-time (JIT) compiler do (in general)? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q84: What is Reactive programming and how does it relate to Angular? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q85: Name some security best practices in Angular ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q86: What is ngUpgrage?  ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q87: How do you create application to use scss? What changed for Angular 6? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q88: Name and explain some Angular Module Loading examples ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q89: Why would you use lazy loading modules in Angular app? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q90: When does a lazy loaded module is loaded? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q91: What is Ivy Renderer? Is it supported by Angular 7? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q92: What is incremental DOM? How is it different from virtual DOM? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q93: Why do we need compilation process? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q94: What are the advantages with AOT? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q95: What are the mapping rules between Angular component and custom element? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q96: Do I need to bootstrap custom elements? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q97: What is the difference between pure and impure pipe? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q98: Angular 8: Why we should use Bazel for Angular builds? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q99: Explain the purpose of Service Workers in Angular ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q100: Angular 9: What are some new features in Angular 9? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q101: What is the difference between BehaviorSubject vs Observable? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q102: What is the Angular equivalent to an AngularJS "$watch"? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q103: Is there no equivalent to `$scope.emit()` or `$scope.broadcast()` in Angular? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q104: Name some differences between SystemJS vs WebPack? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q105: Could you provide some particular examples of using ngZone? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q106: What is the default compilation for Angular 5? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q107: Just-in-Time (JiT) vs Ahead-of-Time (AoT) compilation. Explain the difference. ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q108: Do you know how you can run angularJS and angular side by side? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q109: How would you extract webpack config from angular cli project? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q110: Why angular uses url segment? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q111: When to use query parameters versus matrix parameters? ⭐⭐⭐⭐⭐

**Questions Details:**

* Query parameters: http://example.com/apples?order=random&color=blue
* Matrix parameters: http://example.com/apples;order=random;color=blue


 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q112: Why did the Google team go with incremental DOM instead of virtual DOM? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q113: Why Incremental DOM is Tree Shakable? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q114: What's new in Angular 7? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q115: What are observable creation functions? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q116: Angular 8: How does Ivy affect the (Re)build time? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q117: Angular 8: What are some changes in Location module? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q118: Angular 9: What is Locality principle for Ivy? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q119: Angular 9: Explain improvements in Tree-Shaking ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**


## Q120: Angular 9: How Would You Compare View Engine vs Ivy? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Angular)**
