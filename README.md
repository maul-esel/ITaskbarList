System.Windows.Markup.XamlParseException ist aufgetreten.
  Message=Zeilennummer "66" und Zeilenposition "50" von "Beim Festlegen der Eigenschaft "System.Windows.Data.Binding.Converter" wurde eine Ausnahme ausgelöst.".
  Source=PresentationFramework
  LineNumber=66
  LinePosition=50
  StackTrace:
       bei System.Windows.Markup.XamlReader.RewrapException(Exception e, IXamlLineInfo lineInfo, Uri baseUri)
  InnerException: System.InvalidCastException
       Message=Das Objekt des Typs "System.String" kann nicht in Typ "System.Windows.Data.IValueConverter" umgewandelt werden.
       Source=PresentationFramework
       StackTrace:
            bei System.Windows.Baml2006.WpfSharedBamlSchemaContext.<Create_BamlProperty_Binding_Converter>b__14c(Object target, Object value)
            bei System.Windows.Baml2006.WpfKnownMemberInvoker.SetValue(Object instance, Object value)
            bei MS.Internal.Xaml.Runtime.ClrObjectRuntime.SetValue(XamlMember member, Object obj, Object value)
            bei MS.Internal.Xaml.Runtime.ClrObjectRuntime.SetValue(Object inst, XamlMember property, Object value)
       InnerException: 
