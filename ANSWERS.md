- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.
		They where originally included with react and since have become there own
		packacge that you can include optionally.  They are used to check the types
		of data you are passing around. string, num, etc....  helpful to make sure
		you are passing what you intend to pass.
- [ ] Describe a life-cycle event in React?
		a life-cycle event is a event that goes through changes specifically mount,
		update, and unmount, or birth, growth, and death. at these stages you
		express different things to happen at that life-cycle event.
- [ ] Explain the details of a Higher Order Component?
		a higher order component is basically a function that returns a component.
		you wrap the intended component with the higher order component and don't
		actually call it. therefor you usually name it with a lowercase so as not to
		call it by mistake. also withCompnent as an example. with is often seen and
		recognized as a higher order component by programers
- [ ] What are three different ways to style components in React? Explain some of the benefits of each.
		plain css, pre-proccessors, styled-components, css modules. there are many
		ways to style components. benefit to css is it is the same as it always has
		been and not likely to dissaapear while newer things might lose popularity.
		cssmodules are great that basically contain the class to that file and
		therefore you can use .Button in one file and .Button in another and they
		won't effect each other.  styled comonents is css in js and its cool as you
		can see all of your jsx, js, and css in one file.  not sure i like how it
		changes classnames in dev tools, but its really cool and really easy to use.
