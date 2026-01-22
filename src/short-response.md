# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:**

Accessibility is the practice of developing products, such as websites, that are inclusive for _everyone_ to use. It matters because it allows impaired users to navigate easily (e.g. with screen readers) through the product/website we create. To improve accessibility, programmers can use the `for` attribute in a `<label>` tag and a matching `id` attribute in the `<input>` tag. Additionally, when grouping multiple options, programmers can use the `<fieldset>` and a `<legend>` tag indicating the purpose of the information set.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:**

`name` serves as the placeholder for each piece of data when a dataset receives it.
`for` is used to associate a label to a form control element, such as `input`.
`id` is used to distinguish specific `input` tag.
`for` and `id` work in harmony for accesibility purposes. `for` will create a connection to the `input` label. They need matching names to work properly. 

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:**

We use `type="email"` or `type="number"` because it provides validates the user inputs the correct information for each field. For instance, if `type="email"` is used, it will validate that the input has an email validated format. This prevents that people send any information.

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:**

To create an account on Amazon.com, you need to provide the required information, such as name, email, and password. Then you press **"Create your Amazon account"** and the information is sent to the data server. The data is stored in their database so you can log in. Then you receive a sort of confirmation. Once your account is created and you log in, you provide your information and it goes through a verification process to see if the information matches. If the information matches, permission is granted. It it doesn't the user sees an error message.
