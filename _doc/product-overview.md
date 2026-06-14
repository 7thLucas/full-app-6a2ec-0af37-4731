import 'package:flutter/material.dart';

void main() {
  runApp(const TradingApp());
}

class TradingApp extends StatelessWidget {
  const TradingApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Trading Academy',
      home: Scaffold(
        appBar: AppBar(
          title: const Text('Trading Academy'),
        ),
        body: const Center(
          child: Text(
            'Learn Trading Safely',
            style: TextStyle(fontSize: 24),
          ),
        ),
      ),
    );
  }
}import 'package:flutter/material.dart';

void main() {
  runApp(const TradingApp());
}

class TradingApp extends StatelessWidget {
  const TradingApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Trading Academy',
      home: Scaffold(
        appBar: AppBar(
          title: const Text('Trading Academy'),
        ),
        body: const Center(
          child: Text(
            'Learn Trading Safely',
            style: TextStyle(fontSize: 24),
          ),
        ),
      ),
    );
  }
}