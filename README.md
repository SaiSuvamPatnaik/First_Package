# Custom-Toast Box

A new Flutter package.

## Getting Started

This Package is all about generating a toast box in your project.

## Procedure

1. Just Include the following dependency in your pubspecs.yaml file

    dependencies:
        trial_package: ^0.0.1

2. Install the packages into your project by using the Android studio Terminal by writing the command

    $ flutter pub get

3. Now Import it into your dart file where you want to create a Toast box

    import 'package:trial_package/trial_package.dart';

4. Now You Free to use.

5. Just Include this code inside the onTap() Function

    CustomAlertBox.showCustomAlertBox(
                  context: context,
                  willDisplayWidget: Container(
                    child: Text('Text Of Your Wish'),
                  ));