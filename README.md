# COP2664-1-Recipe-Application-Project
This repository  is a submission link for COP2664-1: Recipe Application Project

import SwiftUI

struct ContentView: View {
    var body: some View {
        TabBar()
    }
} // This is the main view that will be displayed when the app is launched. It contains a TabBar view.

struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
            .environmentObject(RecipesViewModel())
    }
} // This is a preview provider that allows you to see the ContentView in Xcode's canvas. It also provides an environment object for the RecipesViewModel.
