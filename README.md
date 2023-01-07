# AccessControl
Access Control Types



**Access Control**

struct AccessControl {
    private var number: String
    
    init(number: String) {
        self.number = number
    }
    
    public func publicFunc() -> String {
        return "Public function"
    }
}
let object1 = AccessControl(number: "12")
object1.publicFunc()
