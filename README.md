**[See the theme component discussion here on Discourse](https://meta.discourse.org/t/guest-gate-theme-component/225107)**

### Short Description

Hello :wave: This theme component is created from https://meta.discourse.org/t/guest-gate-sign-up-popup-plugin/56625/. It can lock topics for anon visitors with a modal and force them to Sign Up or Login. The component can be use for like an *alert* modal to warn visitors to sign up but they can close it (for this leave uncheck the `dismissable false` setting). You can also change how many topic page view open the modal etc....

### Screenshots

![Screenshot 2022-04-23 at 22 05 29](https://user-images.githubusercontent.com/71207900/164945247-04b20c10-51ba-4d63-a6d1-ace4ccdc6e7f.png)

**Tip:** If you use the custom gate and want to hide the modal header just like on the image above. You have to delete the `guest_gate.title` field and hit a <kbd>space</kbd>. It will remove the modal title, so you can use a title below the image.

![Screenshot 2022-04-23 at 22 03 16](https://user-images.githubusercontent.com/71207900/164945265-80af1181-2ab9-4a44-a1fb-73333b49d2ff.png)

![Screenshot 2022-04-23 at 21 36 30](https://user-images.githubusercontent.com/71207900/164945280-ea0cde9a-a7c3-44f5-b872-7bc9c843b213.png)

### Long Description

**You have two main gate options:**
1. Generic gate (default: it will use the Discourse Signup CTA text in modal)
It uses these texts: `js.signup_cta.intro` and `js.signup_cta.value_prop`

2. Custom gate (you can customize the modal; add image, custom text and colors)

---

**And there are lot of other settings** 

**Guest Gate modal global settings**

![Screenshot 2022-04-23 at 16 42 04](https://user-images.githubusercontent.com/71207900/164945330-ce23cf60-66e9-4d9b-9d51-b524093cb5d4.png)

1. `max guest topic views`
*Number of topic views until gate displays. After the gate first appears, it appears randomly between 1 and this number.*
2. `dismissable false`
*Removes the close button and lock the modal so visitors can't close it.*
3. `use gate buttons`
*Use buttons on modal footer instead of links.*
4. `redirect to home`
*Redirect the visitor after click the Login or Signup button to the homepage and open Login or Signup modal.* Note: If you leave unchecked this than the visitor left on topic page after click the buttons and the Guest Gate modal changes with Login or Signup modal which is dismissable so the visitor can close it and read the topic.
5. `gate footer position`
*Footer buttons/links position.*
6. `gate show only once`
*Guest Gate modal show only once per session.*

---

**Custom Gate settings**

![Screenshot 2022-04-23 at 16 57 11](https://user-images.githubusercontent.com/71207900/164945355-9356d189-9a5c-41c4-bad7-ebee7e7271ae.png)

1. `custom gate enabled`
*Enable it if you want to customize the modal.*
2. `custom gate image`
*Upload an image to top of the modal content.*
3. `custom gate image width`
*The uploaded image width. You can use px, % etc, e.g. 100% will add a full modal width (minus padding) image.* 
4. `custom gate big text color`
*Big text goes to below image. You can set the color of the text.*
5. `custom gate little text color`
*Little text goes to below big text. You can set the color of the text.*
6. `custom gate background color`
*Change the modal background. You can set the background color of the modal.*
7. `custom gate link color`
*Change the footer link color. It appears if the `use gate buttons` setting disable and you set up a custom gate.*

---

> **Credit** :heart:   Huge thanks to the plugin authors, maintainers and contributors: @vinothkannans, @jgujgu and @michaeld 
