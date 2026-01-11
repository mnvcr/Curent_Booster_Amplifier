During the development of a custom system, I required a high-current booster amplifier capable of driving loads beyond the output current capability of a standard operational amplifier. 
While researching suitable architectures, I studied the article “Designer’s Guide to Op-Amp Booster Stages” by Jim Williams, published in EDN on May 29, 1986.
The topology presented in Figure 3 of that article closely matched the required current drive performance and stability characteristics. 
However, the original design did not provide sufficient output voltage swing for my application. To address this limitation, I modified the circuit to operate from increased supply rails of approximately ±22 V.
In addition to extending the voltage range, I incorporated enhanced current monitoring, protection, and control features. 
These functions are implemented using an Arduino-based controller, enabling current limiting, fault detection, and real-time supervision of the booster stage.
