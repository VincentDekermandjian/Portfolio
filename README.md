# Portfolio

	<!-- <p>Who I am?
My name is Vincent Dekermandjian and I am currently student at It-Akademy (Lyon) to be a Full-Stack Developer. I have been into design in all its forms for a longtime, I'm absolutely passionate about designing clear and intuitive interfaces. Being a very curiou evolution of the web always brings me all I need to satisfy my curiosity. I love working on ambitious projects with passionate people and I'm totally open to any offer when it comes to new projects. Now I am looking for an internship in Lyon for February.</p> -->






button on/off 


CSS {
.onoffswitch {
    position: relative; width: 136px;
    -webkit-user-select:none; -moz-user-select:none; -ms-user-select: none;
}
.onoffswitch-checkbox {
    display: none;
}
.onoffswitch-label {
    display: block; overflow: hidden; cursor: pointer;
    border: 2px solid #999999; border-radius: 35px;
}
.onoffswitch-inner {
    display: block; width: 200%; margin-left: -100%;
    transition: margin 0.3s ease-in 0s;
}
.onoffswitch-inner:before, .onoffswitch-inner:after {
    display: block; float: left; width: 50%; height: 24px; padding: 0; line-height: 24px;
    font-size: 18px; color: white; font-family: Trebuchet, Arial, sans-serif; font-weight: bold;
    box-sizing: border-box;
}
.onoffswitch-inner:before {
    content: "English";
    padding-left: 23px;
    background-color: #49E845; color: #FFFFFF;
}
.onoffswitch-inner:after {
    content: "Français";
    padding-right: 23px;
    background-color: #1249E0; color: #FFFFFF;
    text-align: right;
}
.onoffswitch-switch {
    display: block; width: 27px; margin: -1.5px;
    background: #FFFFFF;
    position: absolute; top: 0; bottom: 0;
    right: 108px;
    border: 2px solid #999999; border-radius: 35px;
    transition: all 0.3s ease-in 0s; 
}
.onoffswitch-checkbox:checked + .onoffswitch-label .onoffswitch-inner {
    margin-left: 0;
}
.onoffswitch-checkbox:checked + .onoffswitch-label .onoffswitch-switch {
    right: 0px; 
}


}

<div class="onoffswitch">
    <input type="checkbox" name="onoffswitch" class="onoffswitch-checkbox" id="myonoffswitch" checked>
    <label class="onoffswitch-label" for="myonoffswitch">
        <span class="onoffswitch-inner"></span>
        <span class="onoffswitch-switch"></span>
    </label>
</div>s perfectionist always in quest of novelties, I constantly try to stay open and keep myself informed. In that respect, the
