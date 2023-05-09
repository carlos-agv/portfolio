# SWIFT
[SWIFT](https://developer.apple.com/swift/) para aplicaciones iOS.

```SWIFT
// Ejemplo:
class ViewController: UIViewController {
    @IBOutlet weak var imageView: UIImageView!

    override func viewDidLoad() {
        super.viewDidLoad()
        
        // Agregar controlador gestos
        let gestoP = UIPanGestureRecognizer(target: self, action: #selector(onPan(_:)))
        imageView.isUserInteractionEnabled = true
        imageView.addGestureRecognizer(gestoP)
    }

    @objc func onPan(_ gestoP: UIPanGestureRecognizer) {
        let translation = panGesture.translation(in: view)
        
        // Mover imagen segun DRAG
        imageView.center = CGPoint(x: imageView.center.x + translation.x, y: imageView.center.y + translation.y)
        gestoP.setTranslation(CGPoint.zero, in: view)
    }
}

```
