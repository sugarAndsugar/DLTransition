# DLTransition
一句话边界滑动(Swift)

镜像(Objective - C)
<https://github.com/molon/MLTransition>

原理分析
<https://kakakai.com/2016/04/11/ReadSource/2016-04-11/>

Usage

<pre>
func application(application: UIApplication, willFinishLaunchingWithOptions launchOptions: [NSObject : AnyObject]?) -> Bool {
DLTransition.validatePanBackWithDLTransitionGestureRecognizerType(.DLTransitionGestureRecognizerEdgePan)
return true
}
</pre>