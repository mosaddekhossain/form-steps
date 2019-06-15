# Form Steps

Form steps is a css plugin that makes it easy to create simple, beautiful form steps. 

## Usage
Take the css file.
```html
<link rel="stylesheet" href="css/main.css">
```

Simple markup for First Step
```html
    <nav class="mk-form-steps">
        <div class="mk-form-steps__item mk-form-steps__item--active">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">1</span>
                <span class="mk-form-steps__item-text">Input</span>
            </div>
    
        </div>
        <div class="mk-form-steps__item active">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">2</span>
                <span class="mk-form-steps__item-line"></span>
                <span class="mk-form-steps__item-text">Confirm</span>
            </div>
        </div>
        <div class="mk-form-steps__item">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">3</span>
                <span class="mk-form-steps__item-line"></span>
                <span class="mk-form-steps__item-text">Done</span>
            </div>
        </div>
    </nav>
```

Markup for Second Step active
```html
    <nav class="mk-form-steps">
        <div class="mk-form-steps__item mk-form-steps__item--completed">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">1</span>
                <span class="mk-form-steps__item-text">Input</span>
            </div>
    
        </div>
        <div class="mk-form-steps__item mk-form-steps__item--active">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">2</span>
                <span class="mk-form-steps__item-line"></span>
                <span class="mk-form-steps__item-text">Confirm</span>
            </div>
        </div>
        <div class="mk-form-steps__item">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">3</span>
                <span class="mk-form-steps__item-line"></span>
                <span class="mk-form-steps__item-text">Done</span>
            </div>
        </div>
    </nav>
```    
Markup for Second Step done
```html
    <nav class="mk-form-steps">
        <div class="mk-form-steps__item mk-form-steps__item--completed">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">1</span>
                <span class="mk-form-steps__item-text">Input</span>
            </div>
        
        </div>
        <div class="mk-form-steps__item mk-form-steps__item--completed">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">2</span>
                <span class="mk-form-steps__item-line"></span>
                <span class="mk-form-steps__item-text">Confirm</span>
            </div>
        </div>
        <div class="mk-form-steps__item mk-form-steps__item--active">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">3</span>
                <span class="mk-form-steps__item-line"></span>
                <span class="mk-form-steps__item-text">Done</span>
            </div>
        </div>
    </nav>
```
Markup for Third Step done
```html
    <nav class="mk-form-steps">
        <div class="mk-form-steps__item mk-form-steps__item--completed">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">1</span>
                <span class="mk-form-steps__item-text">Input</span>
            </div>

        </div>
        <div class="mk-form-steps__item mk-form-steps__item--completed">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">2</span>
                <span class="mk-form-steps__item-line"></span>
                <span class="mk-form-steps__item-text">Confirm</span>
            </div>
        </div>
        <div class="mk-form-steps__item mk-form-steps__item--completed">
            <div class="mk-form-steps__item-content">
                <span class="mk-form-steps__item-icon">3</span>
                <span class="mk-form-steps__item-line"></span>
                <span class="mk-form-steps__item-text">Done</span>
            </div>
        </div>
    </nav>
``` 
## Copyright 2019 mosaddek.com
Licensed under the MIT License, http://www.opensource.org/licenses/mit-license.php
     