function onload()
  -- retract side trays on load
  self.interactable = false
end

function retractSides()
  self.AssetBundle.playTriggerEffect(1)
  Timer.destroy("retract_delay")
  Timer.create({identifier="retract_delay", function_name='retractSides2', delay=1})
end

function retractSides2()
  self.AssetBundle.playTriggerEffect(2)
end