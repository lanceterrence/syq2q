# Goal

You must able to identify the reason of why `<aside>` tag is being pushed on next line.

And must also fix it.

### Note

`<section>` tag must have a width of 75%

`<aside>` tag must have a width of 25%

You must not edit `index.html`

# Expected Output

<img src="https://cdn.glitch.com/7373e19d-cfff-4c35-8ae0-a64502512e61%2Fa33902fd-7b6d-44eb-86ed-9a4505811745.image.png?v=1610011580923">

# Your Answer Here

_type here what is the issue and how you solve it_

1. The first issue that I encountered was the spacing of the page, and immediately thought that the spacing was the issue why the module is below the section. So I inputted the code below:

- {
  margin: 0;
  padding: 0;
  box-sizing: 0;
  }

It automatically fixed the spacing of the `<article>` and `<aside>`'s position.

2. The second issue was the padding of the body, it was too large compared with the expected output, so I decreased it from 30px to 3px.

3. The third issue was the line-height of `<article>`, as I am seeing with the expected output the line-height was set to 2. So what I did was I set the line-height of `<article>` to 2.

4. At the expected output, all of the parent containers have some similarity of spacing at the top and bottom inside. So I set additional padding for all the parents at top and bottom (padding).

5. And lastly, for minor sides I added a bottom margin for the `<h3>` tag inside the `<aside>` container. And fixed the padding for the `<section>` container to match the expected output.
