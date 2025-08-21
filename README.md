
def show_greeting():
"""
Prints a static greeting message to the console.
"""
message = "Hello, World! The process has started."
print(message)
<pre><code class="lang-text">Initial commit
</code></pre>

مرحله دوم: ویرایش کد و کامیت آپدیت
حالا فرض کنید می‌خواهیم کد را بهبود ببخشیم تا به جای یک پیام ثابت، بتواند نام یک شخص را بگیرد و پیام را شخصی‌سازی کند.

1. رشته کد جدید و ویرایش شده:

در این نسخه، تابع show_greeting یک پارامتر به نام name دریافت می‌کند.

<pre><code class="lang-python"># main.py

def show_greeting(name="World"):
"""
Prints a personalized greeting message to the console.
:param name: The name to include in the greeting.
"""
message = f"Hello, {name}! The process has started."
print(message)

if name == "main":
# Example of how to use the updated function
show_greeting("Alice")
</
