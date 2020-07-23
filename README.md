Pairings of [in:verse](https://inverse.website/) code and the corresponding compiled GLSL shader (taken from the [gallery](https://gallery.inverse.website/)) were used as prompts to Open AI's GPT-3. <br><br>

See the results [here](http://gpt3.inverse.website/). The generated GLSL was sometimes valid, sometimes needed a bracket or two added or removed from the end, and sometimes needed a comma to be replaced by an arthmetic operator, or the other way around. The code generated from [in:verse](https://github.com/noisyneuron/inverse) flattens the final RGB componenets to a single line, ie `vec3(R,G,B)`, hence making it easier to generate valid code through the prompts.<br><br>

Content might be offensive -- it was often marked as 'toxic', sometimes without apparent reason. <br><br>

These prompts included no special syntax markers for 'start', 'restarting' and 'stopping'... When added, that did yield better results. More on that soon. Currently there is no marking for the prompt vs the generated text. 
