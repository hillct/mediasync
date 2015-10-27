
Media Synchronization

A MediaSync object has been created based on a set of measurements of various browsers.  It connects to an HTML media element and monitors its state.  The state of the media element is then compared to the ideal state provided by the associated Shared Motion.  Any discrepancy is compensated, either by using variable playback rates (if supported) or by skipping.  As media elements are not designed for such external monitoring and control, browsers behave differently.  The underlying operating system might also affect media elements, as do any hardware limitations.  

The MediaSync object tries to automatically determine the best way to synchronize any stream on any browser.  It has been tuned to provide relatively good results on as many browsers and devices as possible, which has led to a very simple solution.  Better synchronization results can be achieved by tuning to specific browser/operating system combinations, but in the MediaScape project, ease of use and general usability has been regarded as more important.  The MediaSync object also provides ample information about it’s current state and limitations, making it possible for the application programmers to detect problems and react to them (for example suggest moving video to a better suited device).

Look in the helloworld folder for an example, or in the API folder for full documentation.