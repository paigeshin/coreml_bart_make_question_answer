### Model

Apple Bart Model

https://developer.apple.com/machine-learning/models/#text

### Swift

```swift
    DispatchQueue.global(qos: .userInitiated).async {
        let answer = self.model.findAnswer(for: self.question, in: self.context)
        self.answerLabel = String(answer)
    }
```
