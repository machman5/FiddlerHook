# FiddlerHook
FiddlerHook for Firefox, modified to work on ALL Firefox versions ("*" in the manifest instead of 4-42 so you can use it in any version).

Either download the master.zip of the repository from GitHub
or clone the repository on your desktop (or something..), then zip it yourself,
than change <code>.zip</code> to <code>.xpi</code> and drag&drop it over an open Firefox window.
Choose "install" and restart your browser, you'll have a small icon to help you set the proxy fast, a.k.a hook/unhook the traffic with fiddler.

An alternative way is to use Fiddler as a man-in-the-middle (checking-ON the option),
allowing connections over the <code>8888</code>, visiting your local address:8888 first clicking the certificate link and installing and trusting the certificate, and than you can change the proxy to your local address with the 8888 port.