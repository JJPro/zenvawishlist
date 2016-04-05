# zenvawishlist
This repo contains the updated code for a reply to a Udemy lecture about Wordpress Plugin Development. 

<a href="https://www.udemy.com/wordpress-plugin-development/learn/v4/t/lecture/317354" target="_blank">Lecture: Wordpress Admin Settings - Udemy</a>

I don't agree with the way the lector uses the WordPress Settings API, therefore, this code repo is created to represent how I think  the Settings API is supposed to be used. 

Here is an excerpt of my reply on the lecture discussion board: 
<blockquote>
I don't think this is the right way to use Settings API. Per do_settings_fields() documentation, it shouldn't be called manually. You are supposed to use add_settings_section() to create a section to the page, then add_settings_field() to add the settings to the section, and then use do_settings_sections($page) to render the page. This way, the table and style is automatically generated by WordPress, you don't need to manually write code to create the table.​​

<p></p><p>
Check this repo for updated code: <br>
https://github.com/JJPro/zenvawishlist
</p>
</blockquote>
