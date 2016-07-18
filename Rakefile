file "index.hiki" => ["index.md", "hiki2md"] do
  sh "./hiki2md < index.md > index.hiki"
end
file "index.html" => ["index.hiki"] do
  sh "hikidoc < index.hiki > index.html"
end
task default: ["index.html"]
