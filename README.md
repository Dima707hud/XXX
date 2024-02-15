# XXXclass SignalBook:
    def __init__(self):
        self.signals = []

    def add_signal(self, signal):
        self.signals.append(signal)

    def remove_signal(self, signal):
        self.signals.remove(signal)

    def get_signals(self):
        return self.signals

    def clear_signals(self):
        self.signals = []

# Example usage
if __name__ == "__main__":
    signal_book = SignalBook()

    # Add signals to the signal book
    signal_book.add_signal("Buy AAPL at $150")
    signal_book.add_signal("Sell MSFT at $200")

    # Get all signals
    print("All signals:", signal_book.get_signals())

    # Remove a signal
    signal_book.remove_signal("Buy AAPL at $150")

    # Get updated signals
    print("Updated signals:", signal_book.get_signals())

    #
