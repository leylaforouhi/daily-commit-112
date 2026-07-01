def reverse_words(sentencE):
    return " ".join(sentence.split()[::-1])

if __name__ == "__main__":
    text = "Daily commits build long term consistency"
    print(f"Original: {text}")
    print(f"Reversed words: {reverse_words(text)}")
